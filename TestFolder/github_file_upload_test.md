###이제 Github 웹에서 파일 업로드가 가능하다고 한다.

```java

//md 문법 확인
import java.util.Scanner;

class TestClass {
	public static void main(String[] args){
		System.out.println("Hello World");
	}
}
```

* 파일을 담은 폴더가 통째로 업로드 되는지 확인한다.
* 확인해보니 파일을 담은 폴더는 폴더 통째로 업로드가 가능하지만 빈 폴더는 업로드 되지 않는다.
* 또한, 같은 이름의 파일을 업로드 할 경우에는 자동으로 덮어쓰기가 된다. 즉 기존의 파일이 수정된다는 것이다.  
  이 과정에서 같은 이름이라고 덮어쓸거냐 이름을 바꿀거냐 같은 질문은 없다. 전혀 다른 파일이 같은 이름이 되지 않도록 주의해야겠다.