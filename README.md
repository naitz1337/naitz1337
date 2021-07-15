```java
public class Naitz {
	class Bio {
		public String name;
		public String skill;
		public String location;

		public void setBio() {
			this.name = "Naitz";
			this.skill = "Backend Developer";
			this.location = "Istanbul, TR";
		}
	}

	class Skills {
		public String[] programming_languages;
		public String[] languages;
		public String location;
		public String[] learning;

		public void setSkills() {
			this.programming_languages = new String[] { "Java", "C#" };
			this.languages = new String[] { "Turkish", "English" };
			this.location = "Istanbul, TR";
			this.learning = new String[] { "Python", "JavaScript" };
		}
	}
}
```
