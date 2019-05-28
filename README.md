
<h1><b>Owen Benson Portfolio</b></h1>

![alt text](https://www.brainyquote.com/photos_tr/en/h/hjacksonbrownjr/382774/hjacksonbrownjr1-2x.jpg )
<details><summary><b> MyWebPage </b></summary>
 <p>
  
  * [here](https://bensonomb.github.io/WebpageOwen/)
  * <i>The Webpage was a good intro to this school year and I found it interesting how we learned about what actual webistes use. At first I thought I was actually good at this subject, but when other kids made their websites I realized how little I know about everything.</i>
 </p>
  </details>
  
 <details><summary><b>Lightning </b></summary>
 <p>
  
  * [here](https://bensonomb.github.io/lightning2/index.html)
  * <i>The Lightning lab was really cool to look at, but I only figuired out how it worked after I finished, when I had time to think it over. It was fun but I really struggled with the major concepts like connecting different classes. I employed my tactic of using random numbers in my code and seeing what happens, then once something cool comes out I go back and see why that is. It comes up with some pretty funky stuff.</i>
 </p>
  </details>
<details><summary><b> Innovation </b></summary>
 <p>
   * [here](https://docs.google.com/presentation/d/1EG7KycvUXMMP7iokVGnlffy8tbBHrrHfQXn3gyLHafw/edit#slide=id.p)
   * <i> This was a veru interesting project to me and I thoughtthat my topic was very interesting. </i>
  </p>
  </details>
<details><summary><b> Dice </b></summary>
 <p>
  
  * [here](https://github.com/ACS-2018-2019/Benson.O/blob/master/Screen%20Shot%202019-05-21%20at%2012.52.06%20PM.png)
  * <i>I was completely and utterly lost on Dice. I had no idea where to start and I even struggled on the minor code. To me, the major concept code like the scanner class is very difficult to wrap my brain around, but In Dice the smaller code (for loops and such) was 
  a challenge by itself. I employed the help of Dr.R, my classmates and even the internet to figuire out why my dice were so wonky, but it was never fixed.</i>
 </p>
 </details>
  
 <details><summary><b> Chemotaxis </b></summary>
 <p>
  
  * [here](https://github.com/ACS-2018-2019/Benson.O/blob/master/Screen%20Shot%202019-05-21%20at%2012.46.03%20PM.png)
  * <i>Chemotaxis was really cool because it had alot of potential to create some fun games. It reminded me of the final project from AP Comp Sci and I wish we had more time to explore the possibilities and really explore what chemotaxis could be. I found the real life application in biology to be cool as well, and I can imagine this code being used for studies.</i>
 </p>
 </details>
  
<details><summary><b> Starfield </b></summary>
 <p>
  
  * [here](https://github.com/ACS-2018-2019/Benson.O/blob/master/Screen%20Shot%202019-05-21%20at%2012.54.15%20PM.png)
  * <i> I was astonished by what the other people made, and I realized just how much I suck at Computer Science. This is the lab I wish was more relaxed with the due date, because it had alot of potential for really awesome code. After seeing some of the 3D projects I was inspired to try something like that but didn't get a chance. I hope we do something in the future similar to this.</i>
 </p>
 </details>
  
 <details><summary><b> St.Thomas </b></summary>
 <p>
  
   *  [here](https://docs.google.com/presentation/d/e/2PACX-1vSP2GNKvvXJNqUpuG9-HYwJcOF9SgRrhvP0IVNJMrkWlJFsjdZhfSBbly79so4iVE1JYtAqScrAQ7IM/pub?start=false&loop=false&delayms=3000)
   * <i>The college presentation was really weird for me, because I did it on my backup college and thus didnt really care about it. I was also caught off-guard presenting day one and I really wish I could have done more research. I didnt focus on the Computer Science part of St.Thomas because if I go there I will go engineering. But I should have done a better job.</i>
 </p>
 </details>

<details><summary><b> Hard Code! </b></summary>
    

  <br/><br/>The following code was difficult because I found the subject matter of LinkedList to be very abstract and hard to imagine. I think that the entire "node" aspect of the LinkedList to be very alien to me, as I am used to the usual data structures which seem somewhat the same in comparison.
<p>


<i>  public static void skipEveryOther(ListNode list)
  {while(list!=null&&list.getNext()!=null) {
    list.setNext(list.getNext().getNext());
    list=list.getNext();
  }
  }
</p>
</details>

<details><summary><b> 2 sources of Pride </b></summary>
 <p>
  <i> I am proud of how I have slowly understood more and more of the grand concepts of Code, which have always been a struggle for me. When I think of the classes from last year, I can finally identify what I was doing and what the code that was given to us was doing. I feel like my grand understanding of code has increased. I am also proud of how much I know about exceptions. I really threw alot of time to learning about what try catch methods do and theyre honeslty one of the only concepts I understand from this year so far. </i><br/>
  
 
   private void inOrder(TreeNode tree) {
    if (tree != null) {
      inOrder(tree.getLeft());
      System.out.print(tree.getValue() + " ");
      inOrder(tree.getRight());
    }
  }
      <br/>
      I am proud of this snippet of code because I actually understand what this is doing for the code, and I understand what this means to the Trre lan. This is a rare opportunuty for me.
 </p>
 </details>

<details><summary><b> Hurdle! </b></summary>
 <p>
    <i>I felt like I did not belong in this clase. I had alot of troubles in this class primarily because I have absolutley no interest in Computer Science, and my lack of interest led me to not care about the class as much. Also, this type of class is very strange to me. I can see why we think that a looser class structure would wokr better, but I now know that I prefere the classic class structure of lecturing and quizess. I was also stricken by multiple techological problems that really restricted me in what I could do.</i>
 </p>
 </details>
 
 <br/><br/>
 
 <i> Markov Chain was very difficult for me, as I could barely understand the concept behind our project. I had to get alot of help from Chris Bartz and Aashish. I think tht this piece of code is one that I am most proud of because I actualy completed a majority of this by myself, adn the rest was given to us.  </i>
    
    '''Java
 
     class MarkovChain implements Markov { List <String> wordList;  Map<String, ArrayList<String>> myMap;  public MarkovChain() {
    wordList=new ArrayList<String>();
    myMap=new HashMap<String, ArrayList<String>>();  }  void trainMap(String [] str) {
    for (int i=0; i<str.length()-1; i++) {
      String currentWord=str[i]; //get first word
      String nextWord=str[i+1];
      if (myMap.get(currentWord==null) {
        myMap.put(currentWord, new ArrayList<String>());
      }
      myMap.get(currentWord).add(nextWord);    }  }  String generateText(String str) {
    String newString="";
    int randomIndex=0;
    int randomIndex2=0;
    if(myMap.containsKey(str)){
    //  randomIndex=getRandomIndex(    }     
     }

    String generateText2(int num) {  }  int getRandomIndex(String s) {
    int randomIndex=(int)(Math.random()*myMap.get(s).size());
    return randomIndex;  }  void printMap() {
    println(myMap);  }  public String toString() {
    return ""+wordList;  }}
  
