# HOT YOGA BRICKELL 
UX/UI Website Redesign - Read case study [here](https://medium.com/@makeespresso/hot-yoga-brickell-e1aa791a1217)

![image](https://user-images.githubusercontent.com/20978259/67951790-8b408780-fbc2-11e9-9f6d-5e43b9cc8371.png)

## Brief
The purpose of this project is to re-design Hot Yoga Brickell website by doing a deep research, business analysis and user testability in order to create a more user-centered allowing the user to accomplish their purposes.

| Section | Updates| 
| :---         |     :---:      |      
| Home  | Remove home from navbar and make the icon an attr to take you to header |
| About     | Brief summary about company's purpose |
| Instructors | Instead of teachers, create a section for each instructor. Reformat content|
|Classes| Include schedule and instructors, preferably create a built-in schedule using Mindandbody 3rd party API|     
| Contact| Leave contact input field, include map and address |
| Footer|Add social networks at the bottom| 


## MVP
* Users are able to look for the classes' schedule
* Users will be able to easily navigate through the website and finding infomation by categories
* Users will be able to buy memberships, add it to cart and check out, with the option to still navigate on the website
* Website re-design
* Mobile first

## POST-MVP
* Utilize 3rd Party API implementation to create a dynamic schedule displaying instrutors and classes
* Mantain and update shopping cart with merchandise
* Users will be able to book classes online
* Recurrent online membership payment
* Monthly newsletter
* Users can register an account on the site
* Seemless UI

## ERD

* User task: To buy a membership

![Hot Yoga Brickell User Flow](https://user-images.githubusercontent.com/20978259/68075229-6fccac80-fd7b-11e9-8c88-bee702a57082.png)

### Current Website State 

![1](https://user-images.githubusercontent.com/20978259/68057792-684eca00-fccd-11e9-91e5-a13e5b1105f8.png)

![2](https://user-images.githubusercontent.com/20978259/68057793-684eca00-fccd-11e9-91ff-e64841b65ff7.png)

![3](https://user-images.githubusercontent.com/20978259/68057794-68e76080-fccd-11e9-8004-04f4f23ac86c.png)

![4](https://user-images.githubusercontent.com/20978259/68057795-68e76080-fccd-11e9-9006-a57806f5fb7d.png)

![5](https://user-images.githubusercontent.com/20978259/68057796-68e76080-fccd-11e9-87cf-d37580ac770e.png)

![6](https://user-images.githubusercontent.com/20978259/68057797-68e76080-fccd-11e9-8317-5b532b9cd983.png)

![7](https://user-images.githubusercontent.com/20978259/68057798-68e76080-fccd-11e9-999f-2bff09b60451.png)

![8](https://user-images.githubusercontent.com/20978259/68057799-68e76080-fccd-11e9-968e-66241f151464.png)

![9](https://user-images.githubusercontent.com/20978259/68057800-68e76080-fccd-11e9-93a4-50a578dcceee.png)

![10](https://user-images.githubusercontent.com/20978259/68057801-68e76080-fccd-11e9-9ec4-0c2891b0afec.png)

## WIREFRAMES

<img width="240" alt="Screen Shot 2019-11-02 at 2 28 10 PM" src="https://user-images.githubusercontent.com/20978259/68075361-0f3e6f00-fd7d-11e9-8671-3c3593a03aa9.png">

<img width="364" alt="Screen Shot 2019-11-02 at 2 21 46 PM" src="https://user-images.githubusercontent.com/20978259/68075368-0fd70580-fd7d-11e9-9595-9ea9e4eda2fc.png">

<img width="364" alt="Screen Shot 2019-11-02 at 2 22 50 PM" src="https://user-images.githubusercontent.com/20978259/68075367-0fd70580-fd7d-11e9-9ffa-63a707b12def.png">

<img width="364" alt="Screen Shot 2019-11-02 at 2 23 53 PM" src="https://user-images.githubusercontent.com/20978259/68075366-0fd70580-fd7d-11e9-9325-571c2bf15db5.png">

<img width="362" alt="Screen Shot 2019-11-02 at 2 25 03 PM" src="https://user-images.githubusercontent.com/20978259/68075365-0f3e6f00-fd7d-11e9-9a48-faf10fc48e90.png">

<img width="365" alt="Screen Shot 2019-11-02 at 2 25 42 PM" src="https://user-images.githubusercontent.com/20978259/68075364-0f3e6f00-fd7d-11e9-80f1-b370259a4d1c.png">

<img width="365" alt="Screen Shot 2019-11-02 at 2 26 16 PM" src="https://user-images.githubusercontent.com/20978259/68075363-0f3e6f00-fd7d-11e9-95e6-e0f5da001076.png">

<img width="365" alt="Screen Shot 2019-11-02 at 2 27 00 PM" src="https://user-images.githubusercontent.com/20978259/68075362-0f3e6f00-fd7d-11e9-833b-52150f7892ca.png">

# React Component Hierarchy
* **\<App />**
* \<header>
  * \<nav>
    * \<AboutUs/>
    * \<Classes/>
        * \<Schedule/>
        * \<Instructors/>
    * \<Workshops/>
        * \<Certifications/>
    * \<Contact/>
         * \<Location/>
* \<footer>













