class Teacher{
	String name,dept,subject;
	int experiance;

	
	public Teacher(String name,String dept,int experiance,String subject){
		this.name = name;
		this.dept=dept;
		this.experiance =experiance;
		this.subject = subject;
	}
	public String getDept(){
	
		return dept;
	}
	public void  setDept(String dept){
		this.dept = dept;
	}
	public void setName(String name){
		this.name=name;
	}
	public void setSubject(String subject){
		this.subject=subject;
	}
	public String getSubject(){
		return subject;
	}
	public String getName(){
		return name;
	}
	public int getExp(){
		return experiance;
	}
	public void setExp(int experiance){
		this.experiance = experiance;
	}
	// public String info(){
	// 	return ["Teacher name :"+name+" department :"+dept+" Experiance : "+experiance];
	// }
}
class AssociateProfesor extends Teacher{

    private String phdDegree;

    public AssociateProfesor(String name ,String dept,int  exp,String subject,String phdDegree){
        super(name ,dept ,exp,subject);
        this.phdDegree = phdDegree;
        
    }

}
