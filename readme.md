# swift ui

[출처](https://developer.apple.com/tutorials/swiftui/creating-and-combining-views)

````
    var body: some View {
        Text("Hello, World!") # text를 추가 할 수 있다
            .padding() # top, right, bottom, left padding이 추가 된다
	    .font(.title) # method로 추가해서 해당 text의 속성?을 수정 할 수 있다
            .foregroundColor(.green)
    }
````

````
var body: some View {
        VStack { # vertical로 컨텐츠가 배치 된다. VStack(alignment: .leading) { } Vstack, Hstack도 함수? 처럼 사용할 수 있다. 왼쪽 정렬 
            Text("Turtle Rock")
                .font(.title)
            Text("Joshua Tree National Park")
        }
    }
````
