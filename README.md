# Ex-2-Create a player movement using character, collectable, player health and score 

# AIM:
 To Create a player movement using pawn, collectible, player health and score.

 # PROCEDURE:
* Create a new project in Unreal Engine and choose a template that suits your needs.
* Add anewactor to the level and call it "Coin".
* Create a new blueprint based on the Coin actor byselecting it in the Content Browser and
* choosing "Create Blueprint".
* Openthe Coin blueprint and add a static meshcomponent to represent the coin. You can
 import a 3D model or use one of the default shapes provided by Unreal Engine.
* Add acollision component to the Coin blueprint so that the player can interact with it.
 Choose a simple collision shape like a sphere or a box.
* Add acollision component to the Coin blueprint so that the player can interact with it.
 Choose a simple collision shape like a sphere or a box.
* Create a new blueprint based on the player character byselecting it in the Content
 Browser and choosing "Create Blueprint".
* Openthe player blueprint and add a collision component to represent the player's
 interaction with the coins.
* Add anevent to the player blueprint that gets triggered when the player collides with a
 coin. Use a collision event and check if the collided actor is a coin.
* If the collided actor is a coin, check if it has already been collected. If not, set its
 IsCollected variable to true and add its value to a score variable in the player blueprint.
* Remove the coin fromthe level bycalling its Destroy function.
* Add several instances of the Coin actor to the level and adjust their positions so that they
 are spread out and not too close to each other.

# OUTPUT:
![image](https://github.com/user-attachments/assets/b0b7dea0-d94d-48c9-8988-40af7b29b1c5)
![Screenshot 2025-05-15 105726](https://github.com/user-attachments/assets/8ddd695a-acc2-4f35-baae-a31e98250d13)
![image](https://github.com/user-attachments/assets/99cfc606-3a20-4d24-8c1d-11b5cdb61731)


# RESULT:
 Thus the player movement using pawn, collectible, player health, and score has been created and
 developed by unreal Engine.
