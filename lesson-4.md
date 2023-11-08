
# data structures and algorithms

## Previous hw
- send resume
- 5 postings on jobs
- research
    - unit testing in spring
    - software testing pyramid
    - unit testing with mocks
- mongo with spring: https://spring.io/guides/gs/accessing-mongodb-data-rest/

## Algorithm & data structures
- running time (complexity), bigO notation, time complexity
- sorting and searching
- multi threading, recursion
- refactoring

## Professional development
- looking at job postings*
- agile, ways of working
- understanding role of software in business

## Example

searchTerm = "apple"
searchlist = ["pears", "strawberry", "steak", "apple"]

represent favourite fruit of children

searchlist = [
i  j  0          1      2        3
0   ["pears", "strawberry"], 
1   ["apple", "steak"],
2   ["apple", "steak","liions","books"]]

for each item in searchlist as i
    for search sublist in searchlist[i] as j
        if sublist[j] == searchTerm
            return true

time complexity: O(n^2)


### option 1: search each item
for each item in searchlist
    if searchTerm == searchlist[i] - 1s to check
        return true

time for calculation = time of algorithm * n
O(n) - big O of N



*BigO notation* 
represents limiting factors of algorithm at large numbers


### option 2: sort first alphabetically
sort searchList
// write some way to get to correct location first

### option 3: complete random
while matchNotFound
    if searchList[random%searchList.length] == searchTerm
        return true

### option 4: concurrency - multi-threading

bool searchFound = false
splitList[][] = searchList[].split

for each splitList[]
    new thread(searchInSublist(splitList[x]))


func searchInSublist(subList)
    for each in subList
        if subList[x] == searchTerm
            searchFound = true
    return false


## HW
- fix resume
- try mongo w local

## Homework
- try doing very simple algorithms interview questions (google 'easiest coding interview questions')
- research 
    - searching algorithms
    - bigO notation
    - refactor
    - SOLID principles of OOP
    - concept of oop
    - functional programming

Bonus
- rest service: https://spring.io/guides/tutorials/rest/
