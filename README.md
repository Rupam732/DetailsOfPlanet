class Planet{
	String Name;
	String Gas;
	int Moons;
	String Rings;
	
	public void setData(String Name, String i, int Moons, String Rings) {
		this.Name = Name;
		this.Gas = i;
		this.Moons = Moons;
		this.Rings = Rings;
	}

	public String getName() {
		return Name;
	}
	
	public String getGas() {
		return Gas;
	}
	
	public int getMoons() {
		return Moons;
	}
	
	public String getRings() {
		return Rings;
	}
public static class DetailsOfPlanet {

	public static void main(String[] args) {
		 Planet p1 = new Planet();
		 p1.setData("Mercury"," ", 0, "No");
		 Planet p2 = new Planet();
		 p2.setData("Venus","Carbon Dioxide, Nitrogen" , 0, "No"); 
		 Planet p3 = new Planet();
		 p3.setData("Earth","Nitrogen, oxygen" , 1, "No");
		 Planet p4 = new Planet();
		 p4.setData("Jupitor","Hydrogen, Hellium" , 79, "Yes");
		 Planet p5 = new Planet();
		 p5.setData("Saturn","Hydrogen, Hellium" , 83, "Yes");
		 Planet p6 = new Planet();
		 p6.setData("Urenus","Hydrogen, Hellium, Methane" , 27, "Yes");
		 
		 System.out.println(p1.getName()+" "+  p1.getGas()+" " +p1.getMoons()+" "+ p1.getRings());
		 System.out.println(p2.getName()+" "+  p2.getGas()+" " +p2.getMoons()+" "+ p2.getRings());
		 System.out.println(p3.getName()+" "+  p3.getGas()+" " +p3.getMoons()+" "+ p3.getRings());
		 System.out.println(p4.getName()+" "+  p4.getGas()+" " +p4.getMoons()+" "+ p4.getRings());
		 System.out.println(p5.getName()+" "+  p5.getGas()+" " +p5.getMoons()+" "+ p5.getRings());
		 System.out.println(p6.getName()+" "+  p6.getGas()+" " +p6.getMoons()+" "+ p6.getRings());
	}

}
}
