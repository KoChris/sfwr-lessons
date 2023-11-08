
# Security & Auth

## past hw
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

## Professional
- Resume
- Applying for jobs
- handling soft skills questions

## Concepts 
- Authentication vs authorization
- certificates (TLS vs MTLS)
- jwt & oauth

## hw
- update resume
- finish tutorial
- apply to 3 jobs 
    - find 6-10 potential jobs that youre intested in
    - check application deadline
    - apply to non-critical or practice role

- spring application
https://www.baeldung.com/spring-security-oauth-jwt-legacy


## Notes

Declarative vs imperative

goals:
- take cloth and turn it into clothes

Imperative Java
public Clothes process(Cloth input){
    squareBlockOfCloth = rawClothProcesser.cut(input)
    jacketFrame = tailor.createJacketFrame(squareBlockOfCloth)
    jacket = detailer.addButtonsAndPockets(jacketFrame)
    
    return jacket
}

Declarative / Functional programming
public Clothes process(Cloth input){
    return input
        .cutAndProcessed()
        .turnedIntoJackFrame()
        .addedButtonsAndPockets();
}

public SquareBlockOfCloth cutAndProcessed(Cloth )
public JacketFrame turnedIntoJackFrame(squareBlockOfCloth)


Polymorphism

add(int x, int y)
add(floats x, floats y)
add(double x, double y)



Meat extends Food
Vegetable extends Food

class house (){

    private Oven houseOven;

    makeDinner(){
        List[Food] ingrediants = grabFoodFromFridge()
        for each food in ingrediant
            oven.cook(food)
    }

}

class oven {

    public CookedFood cook(Meat meat, Vegetable meat){
        apply fire on meat
        return CookedFood
    }

    public CookedFood cook(Vegetable vege){
        apply less fire on vege
        return CookedFood
    }

}

class woodOven extends over {

    @Overide
    cook(Meat meat)){
        light fire
        apply fire on meat
        return cookedMeat
    }

}


Extends

class vehicle {
    public int passenger-capacity
    public int wheels

    public getInVehicle(){
        hop in
    }

    private startEngine(){
        start combustionInEnginer
    }

    private static startCheckGas(){
        start combustionInEnginer
    }
}

class car extends vehicle{
    passenger-capacity = 5
    wheels: 4

    @Override
    public getInVehicle(){
        open door
        hop in
    }
}

class motorcycle extends vehicle {
    passenger-capacity = 1
    wheels: 2

}

