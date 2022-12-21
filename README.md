## Hi ! I'm 2dongyeop

### 🧑🏻‍💻 A little more about me
<img align="right" src="https://github.com/2dongyeop/2dongyeop/blob/main/horong.jpeg" width=220 />


```Java
public class Introduction {

    private final LeeDongyeop leeDongyeop;
    
    @Autowired
    public void Introduction() {
        leeDongyeop = LeeDongyeop.getInstance();
        
        leeDongyeop.logic();
    }

    static class LeeDongyeop {

        private final String skill;
        private static LeeDongyeop leeDongyeop = new LeeDongyeop("Java");

        private LeeDongyeop(String skill) {
            this.skill = skill;
        }

        public static LeeDongyeop getInstance() {
            return leeDongyeop;
        }

        public void clear() {
            System.out.println("I'm looking for a job. Please contact me!");
        }
        
        public void logic() {
            System.out.println("My main specialty is consistency and habit of recording.");
            System.out.println("I'm interested in web development using Spring, 
                and I'm learning intensively about lambda and streams among Java 8 grammar!");
        }
    }
}

```

<br/>

### 💻 I'm learning now :
- Spring을 이용한 웹 개발에 관심이 있고, Java 8 문법 중 람다와 스트림에 대해 집중적으로 학습 중입니다! 

<br/>

### 🗒 I record what I study on my blog and Notion!
- [TIL](https://github.com/2dongyeop/TIL) : 공부한 CS 지식들을 정리합니다. 
- [Velog](https://velog.io/@dongvelop) : 회고록과 오류 해결 사항들을 기록합니다.
- [Notion](https://www.notion.so/leedongyeop/Dongvelop-s-Notion-ver-2aa4b1990311424789421e0c3cae453e) : 모든 학습 내용을 기록하는 습관을 들입니다.

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=2dongyeop&hide=TeX&layout=compact)
