# polimorfismo
package soma;

public class soma {
	public int add(int n1,int n2){
		return (n1+n2);}
	public int add(int n1,int n2,int n3){
		return (n1+n2+n3);}
	public int add(int n1,int n2,int n3,int n4){
		return (n1+n2+n3+n4);}
		}

public class testar {
public static void main (String []args){
		soma s = new soma();
		System.out.println(s.add(5,5));
		System.out.println(s.add(3,5,4));
		System.out.println(s.add(9,9,9,9));
		}}
