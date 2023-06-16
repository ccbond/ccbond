```rust
struct Attributes;

impl Attributes {
    fn contact() -> (String, String, String) {
        let discord = String::from("Bond#8149");
        let email = String::from("hgamiui9@gmail.com")

        (discord, email)
    }

    fn life() -> (Vec<String>, u32) {
        let langs = vec![
            String::from("Chinses"),
            String::from("English"),
        ];
        let age = 17;

        (langs, age)
    }

    fn coding() -> (Vec<(String, Vec<String>)>, Vec<String>, Vec<String>) {
        let mut langs = Vec::new();
        langs.push((String::from("expert"), vec![String::from("go")]));
        langs.push((String::from("intermediate"), vec![String::from("rust"), String::from("typescript"), String::from("python")]));
        langs.push((
            String::from("learning"),
            vec![
                String::from("move"),
                String::from("c++"),
                String::from("c"),
            ],
        ));

        let specialities = vec![
            String::from("smart contract engineering"),
            String::from("fullstack engineering"),
        ];
        let environnement = vec![String::from("vscode")];

        (langs, specialities, environnement)
    }
}
```
