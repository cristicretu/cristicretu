## Hi there, I'm Cristi 👋

```swift
import Foundation

class About: Me {

    func getLanguages() -> [String] {
        return ["C/C++", "Python", "Javascript", "Swift"]
    }

    func getFutureGoal() -> String {
        return "Contribute to open source & start freelancing"
    }

    func reachMe() -> String {
        return "https://twitter.com/cristicrtu"
    }

    func getPassions() -> [String] {
        return ["Graphic-design 👨‍🎨", "Cycling 🚲"]
    }
    
    func getGithubViews() -> Int {
        print(profileCounter)
    }
    
}
```
```swift
var preview = About()
preview.getGithubViews()
```
<img src="https://profile-counter.glitch.me/cristicretu/count.svg" />
