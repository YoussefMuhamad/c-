#include<iostream>
#include<stdlib.h>
#include<string>
using namespace std;

class User_Name{
	public:
		User_Name(string z_name){
			setName(z_name);
		}
		void setName(string x_name){
			name = x_name;
		}
		string getName(){
			return name;
		}
	private:
		string name;
};

class User_Age{
	public:
		User_Age(int z_user_age){
			setUser_Age(z_user_age);
		}
		void setUser_Age(int x_user_age){
			user_age = x_user_age;
		}
		int getUser_Age(){
			return user_age;
		}
	private:
		int user_age;
};

class Pet_Name{
	public:
		Pet_Name(string z_pet_name){
			setPet_name(z_pet_name);
		}
		void setPet_name(string x_pet_name){
			pet_name = x_pet_name;
		}
		string getPet_name(){
			return pet_name;
		}
	private:
		string pet_name;
};

class User_Mother{
	public:
		User_Mother(string z_name_mother){
			setUser_Mother(z_name_mother);
		}
		void setUser_Mother(string x_name_mother){
			name_mother = x_name_mother;
		}
		string getUser_Mother(){
			return name_mother;
		}
	private:
		string name_mother;
};

class User_Father{
	public:
		User_Father(string z_name_father){
			setName_Father(z_name_father);
		}
		void setName_Father(string x_name_father){
			name_father = x_name_father;
		}
		string getName_Father(){
			return name_father;
		} 
	private:
		string name_father;
};
int main(){
	
	User_Name Obj_User_Name("Youssef Muhamad");
	User_Age Obj_User_Age(16);
	User_Mother Obj_User_Mother("Shalalalal");
	Pet_Name Obj_Pet_Name("Mel");
	User_Father Obj_User_Father("Alwahahwhwa");
	
	cout << Obj_User_Father.getName_Father() << " and " << Obj_User_Mother.getUser_Mother() << " had " << Obj_User_Name.getName() <<
	" and He has his pet " << Obj_Pet_Name.getPet_name() << endl; 
	
	system("pause");
	return 0;
}
