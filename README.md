  public class Schaefer extends Human implements Gamer, Developer {

	@Override
	public String getName() {
		return "Furkan";
	}
	
	@Override
	public List<String> getAliases() {
		return Arrays.asList("Schaefer", "My Name");
	}

        public Schaefer() {
        super("Schaefer", "Earth");

        this.addLanguage("Java", "Python", "Javascript", "Kotlin");
        this.addExperience("2 Years+(java)", "1year+(python)", "2months+(kotlin)", "1 year (js)");
     }
   }

	@Override
	public String aboutme() {
		return "I like to expose people lmao" +
		"\n" + "I like to code Java";
	}
    
	@Override
	public void codingStuff() {
		String[] learning = ["Java", "Node.js / Discord.js", "Python"];
		String tryingTo = "Coding unique plugins/clients and apps.";
	}
	
} 


public abstract class Human {

  @Getter private final String username;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public Human(String username, String placeilive) {
      this.name = username;
      this.country = placeilive;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}



</td></tr></table>  

<br/>  


## Connect with me  
<div align="center">
<a href="https://instagram.com/beautybloodtr" target="_blank">
<img src=https://img.shields.io/badge/instagram-%23000000.svg?&style=for-the-badge&logo=instagram&logoColor=white alt=instagram style="margin-bottom: 5px;" />
</a>
</div>  
  

<br/>  


## Github Stats  
<div align="center"><img src="https://github-readme-stats.vercel.app/api?username=beautybloodtr&show_icons=true&count_private=true&hide_border=true" align="center" /></div>  

<br/>  


## 
   

<div align="center"></div>
<br />
