
```swift
final class Lloople: Developer {

  static let name: String = "David Llop"
  
  static let location: String = "Girona"
  
  func work() -> Company {
    return Company(
      name: "GNA Hotel Solutions", 
      as: "Lead Backend Developer"
    )
  }
  
  func website() -> String {
    return "https://davidllop.com"
  }
  
  func contact(mail: Mail) -> Bool {
    return Mailer().to("d.lloople@icloud.com").send(mail)
  }
}
```
