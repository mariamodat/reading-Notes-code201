# HTML Texts 
 * Headings and paragraphs : HTML has six "levels" of 
headings 1. < h1> is used for main headings
         2.   < h2> is used for subheadings If there are further sections under the subheadings. 
         3.  < h3> element is used, and so on...
 
    **paragraphs** : By default, a browser will show each paragraph on a new line  with some space between it and  any subsequent paragraphs

 * **Bold** : The < b> element also represents a section of text that would be 
presented in a visually different.
 * *italic* :  By enclosing words in the tags < i> and </ i> we can make 
characters appear italic.

![img](https://i.ytimg.com/vi/QfXvonM_MLc/maxresdefault.jpg)
  
  | type | use |
  |------|-----|
  |< sub> | used to make a character as a subscript |
  | < sup> | used to make a character as a supscript |
  | < br /> | line space | 
  | < hr/> | To create a break between themes ,to change the topic |
   
  
  # Structural and semantic markup

  **what is Semantic mean ? e text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages**
   ![img2](https://cdn.educba.com/academy/wp-content/uploads/2019/12/HTML5-Semantic-Elements.jpg)

   |type | use |
   |-----|-----|
   | < strong> | The use of the < strong> element indicates that its content has strong importance. |
   | < em> | By default browsers will show the contents of an < em> element in italic |
   | < blockqoute> | used for longer quotes that take up an entire paragraph |
   | < q> | used for shorter quotes that sit within a paragraph. |
   | < abbr> | to use an abbreviation or an acronym, like Prof .. |
   | < cite > | When you are referencing a piece of work such as a book, film or research paper | 
   | < dfn> | The first time you explain some new terminology | 
   | < address> | to contain contact details for the author of the page , it may appear in *Italic* |
   | < ins> & < del> | The < ins> element can be used to show content that has been inserted into a document, while the < del> element can show text that has been deleted from it. |
   | < s> | The < s> element indicates something that is no longer accurate or relevant (but that should not be deleted). |

   # Introducing CSS 

  ## what is CSS ? 
  **CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.**
## how we can use CSS in HTML file ?
* **inline**  
![img3](https://miro.medium.com/max/1772/1*vMDthM9qBLsONvClseM_ew.png)

* **enternal and external**
![img4](https://www.bitdegree.org/learn/storage/media/images/8c4493d3-110c-4a95-8b70-7626ce2d2f4e.jpg)
 
 # Baisic JavaScript Instructions 
  ![img5](https://lh3.googleusercontent.com/proxy/fm1pnUb93EkSM3mRmw5jYaU92euVCJ0TFkWOCyd7JABu3sMfZY1rT_k-DKeOWM2v83nQKljdehMqvqKCbM97Tj5QpsagVua74GtlQKVrCflwRTpviAyWYyrmiGVt-vxW7PCR3ruHqM_Tng)

  ## statements 
  A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon. 
  ![img6](https://www.tutorialspoint.com/javascript/images/switch_case.jpg)

 ## Comments 
 we use comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. by using the expression // 
 or /* the comment between */

 ## Variables 
  what is the variable ?
   A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables. 
   ### the use of Variables 
   The use of variables to represent numbers or other kinds of data is very similar to the concept of algebra (where le.tters are used to represent numbers). 
    ![img7](https://www.tutsmake.com/wp-content/uploads/2020/05/JavaScript-Variable-Example.jpeg) 

# Data Type 
 |type | exaple |
 |-----|------|
 | string | anything goes between ' ' or " " |
 | Numbers | 1, -2 , 2.5 |
 |boolean | True or False |

 ## changing the value of a Var 
 Once you have assigned a value to a variable, you can then change what is stored in the variable later in the same script. Once the variable has been created, you do not need to use the var keyword to assign it a new value. You just use the variable name, the equals sign (also known as the assignment operator), and the new value for that attribute. 
 
 ## Rules of Naming Var 
 1. The name must begin with a letter, dollar sign ($),or an underscore (_)It must not start with a number. 
 2. can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name
3. use keywords or reserved words. Keywords are special words.
4. All variables are case sensitive
5. Use a name that describes the kind of information that the variable stores.
6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. 

 # Arrays 
 **what is Array ?**
 An array is a special type of variable. It doesn't just store one value; it stores a list of values.
 **when we use it?**
 You should consider using an array whenever you are working with a list or a set of values that are related to each other. 

## Values in Array 
Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).
Ex : var colors; 
colors= ['whi te ' , 
'black ' , 
' custom '];
 so the index of the values are ordered like this : 

**INDEX VALUE** 
o 'white ' 
'bl ack' 
2 ' custom' 
and we can change the value by using : ** colors[ 1]='orange '
 
 # Expressions 
 An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions. 
 1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE : let x = 2 ; 
 2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE :
  let y = 3*x ; 

  # Operators 
  Expressions rely on things called operators; they allow programmers to create a single value from one or more values. 
  ![img8](https://lh3.googleusercontent.com/proxy/eDQk7-Eueq6tmVLRC0QTUgli84uovhp5gY2iwJL0Pd48V0xxNNwd4iMvmK9swz8RT_j2E4EO0H_1StkXvZ1dKrk3AEKwDyLYIkdBt_zjNcovFhmekGhhNBpcSQG-3hTC1ffwenQcqOot1ECC)