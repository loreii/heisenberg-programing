# heisenberg-programing
From an idea of a really"smart" colleague, the implementation of the base of heisenberg programing written in java. 

## 1.Intro
 Heisenberg's uncertainty principle, is any of a variety of mathematical inequalities asserting a fundamental limit to the 
 precision with which certain pairs of physical properties of a particle known as complementary variables, such as position
 x and momentum p, can be known simultaneously. Introduced first in 1927, by the German physicist Werner Heisenberg, it 
 states that the more precisely the position of some particle is determined, the less precisely its momentum can be known, 
 and vice versa.[1]
 
## 2.Programming
 Maching the long story short I look someting but my obeservation change it.
``` 
  /**
   * 
   * @author Mirmo
   *
   */
  public class HeisenbergClass {
  
  	boolean b = false;
	
  	@Override
  	public String toString() {
  		String str = Boolean.toString(b);
  		b=Math.random()> Const.h /2;
  		return str;
  	}
	
  }
```
## 3.Conclusion
 A smart way to loose time if yuo are not handling with quantum cryptography but with some REST services,
 this project is a joke if you have some doubts. 
 
 
## 4.Resources
 [1]http://en.wikipedia.org/wiki/Uncertainty_principle
 
 
 
 
 
 
