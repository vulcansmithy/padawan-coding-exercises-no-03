##Coding Exercises No. 03
1. In this exercise, I want you to clone a git repo and prepare your local repository.

 **1.1**&nbsp;&nbsp;&nbsp;Create a new repository at github.com. Give it name of **padawan-coding-exercises-no-03**. Don't initialize it with a README, .gitignore, or license
    
 **1.2**&nbsp;&nbsp;&nbsp;Clone this remote repository to your local machine
 
 ~~~bash
$> git clone https://github.com/vulcansmithy/padawan-coding-exercises-no-03.git 
~~~ 

 **1.3**&nbsp;&nbsp;&nbsp;Rename the local repository's current 'origin' to 'upstream'
 
 ~~~bash
$> git remote rename origin upstream
~~~ 

 **1.4**&nbsp;&nbsp;&nbsp;Give the local repository an 'origin' that points to your repository
 
 ~~~bash
$> git remote add origin https://github.com/KrstnP/padawan-coding-exercises-no-03.git
~~~ 

 **1.5**&nbsp;&nbsp;&nbsp;Push the local repository to your repository on github
 
 ~~~bash
$> git push origin master
~~~ 
&nbsp;

2. Give the formula for computing the **Area of a Circle** 
&nbsp;
\\[
A = pr^2
\\]
&nbsp;
 wherein,
 &nbsp;&nbsp;&nbsp;&nbsp;**p**&nbsp;&nbsp;represent the value of Pi, **3.141592653589793** 
 &nbsp;&nbsp;&nbsp;&nbsp;**r**&nbsp;&nbsp;is a given radius
 
  write a program that uses a constant variable to reprsent the value of **pi**, which is **3.141592653589793**, and compute the Area of the Circle. Then display the result on the screen. 
 
 ~~~ruby
<a ruby constant variable> = 3.141592653589793
radius = 250
area_of_a_circle = <a ruby constant variable> * (radius ** 2)
<ruby code to display the result to the screen>
~~~ 
&nbsp;

 Additional challenge. Do a quick research on the internet and figure out what does this part of code above means

 ~~~ruby
radius ** 2
~~~ 

 What does **\*\*** means. [Clue](https://www.ruby-forum.com/topic/76409).

3. Given the formula for computing the **Circumference of a Circle** 
\\[
C = pd
\\]
 wherein,
    * **p** represent the value of Pi, **3.141592653589793**
    * **d** is a given diameter of a circle

 write a program that uses a constant variable to reprsent the value of **pi**, which is **3.141592653589793**, and compute the Circumference of a Circle. Then display the result on the screen. 
&nbsp;

4. Given you have a hash called **h**

 ~~~ruby
h = { :key_a => 35, :key_b => 84.50, :key_c => true, :key_d => "grace" } 
~~~ 
write a ruby program that retrieve the value of 35 from the
hash. Then display the retrieve value using the String interpolation. The output should looks like this

 ~~~
Retrieved the value 35 from the hash variable 'h'
~~~  
&nbsp;

5. Given you have a hash called **h**

 ~~~ ruby
h = { :key_a => 35, :key_b => 84.50, :key_c => true, :key_d => "grace" } 
~~~ 
 
 write a ruby program that change the value of what **:key_c** is associated with. Change it from **true** to **false**. Then output the new value of **key_c** to the screen. The output should look like below. Again, use String interpolation to display the result.
 
 ~~~
The new value of h[:key_c] is now false.
~~~ 
&nbsp;

6. Given the following key-value pair

 ~~~
key..... :first_name
value... "Matt" 
~~~
 ~~~
key..... :last_name
value... "Murdock"
~~~
 ~~~
key..... :occupation
value... "Lawyer"
~~~
 ~~~
key..... :company
value... "Nelson and Murdock Attorneys at Law"
~~~
 ~~~
key..... :email1
value... "mattDD@hellskitchen.com"
~~~
 ~~~
key..... :email2
value... "mattDD@nelson_and_murdock.com"
~~~ 

 write a ruby program that contains a hash called **contact_info**. Use the above list as the values stored in the **contact_info** hash variable.
&nbsp;
 
7. Given the following key-value pair

 ~~~
key..... :title
value... "The Mysterious Affair at Styles"
~~~
 ~~~ 
key..... :author
value... "Agatha Christie"
~~~
 ~~~ 
key..... :year_published
value... 1920
~~~
 ~~~
key..... :genre
value... "Crime Novel"
~~~

 write a ruby program that contains a hash called **book_card**. Use the above list as the values stored in the **book_card** hash variable.
&nbsp;

8. Using the hash given in exercise no. 5, write a program that delete or remove a specific key-value pair stored in the hash **h**. The one that you're going to remove is the **:key_c**. Once the key-value pair is remove, display to the screen the update content of the hash **h**. [Clue](https://docs.ruby-lang.org/en/2.0.0/Hash.html).
&nbsp;

9. Using the hash given in exercise no. 6, write a program that would display all the **keys** used in hash **contact_info**. To retrieve the **keys** used, there is a function or method that you can call. Do a research on internet to figure out what is this method or function that you can use. [Clue](https://docs.ruby-lang.org/en/2.0.0/Hash.html#method-i-keys).
&nbsp;

10. Using the hash found in exercise no. 6, write a ruby program that would iterte to each key-value pair in the hash **contact_info**. [Clue](https://docs.ruby-lang.org/en/2.0.0/Hash.html#method-i-each). The code should look like something like

~~~ruby
contact_info.[insert method here] do |[insert something here],[insert something here]|
 puts "key... #{[insert something here]}, value... #{[insert something here]}"
end 
~~~ 
&nbsp;


 
 