# HOT YOGA BRICKELL 
UX/UI Website Redesign Case Study

![image](https://user-images.githubusercontent.com/20978259/67951790-8b408780-fbc2-11e9-9f6d-5e43b9cc8371.png)

## Brief
The purpose of this project is to re-design Hot Yoga Brickell website by doing a deep research, business analysis and user testability in order to create a more user-centered allowing the user to accomplish their purposes.

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



| Section | Updates| 
| :---         |     :---:      |      
| Home  | Remove home from navbar and make the icon an attr to take you to header |
| About     | Brief summary about company's purpose |
| Instructors | Instead of teachers, create a section for each instructor. Reformat content|
|Classes| Include schedule and instructors, preferably create a built-in schedule using Mindandbody 3rd party API|     
| Contact| Leave contact input field, include map and address |
| Footer|Add social networks at the bottom| 


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


## MVP
* Users are able to look for the classes' schedule
* Users will be able to easily navigate through the website and finding infomation by categories
* Users will be able to buy memberships, add it to cart and check out, with the option to still navigate on the website
* Website re-design
* Mobile first

## POST-MVP
* Utilize 3rd Party API implementation to create a dynamic schedule displaying instrutors and classes
* Mantain and update shopping cart
* Users will be able to book classes online
* Recurrent online membership payment
* Monthly newsletter






