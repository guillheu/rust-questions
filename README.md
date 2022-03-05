## Q1

Will this code compile ?
```
fn main() {
    let mut a = 7;
    
    let b = &mut a;     

    println!("{}", b);
    *b += 1;
    println!("{}", b);

    println!("{}", a);
    a += 1;
    println!("{}", a);
}
```

<details>
<summary>Answer :</summary>

 * Yes

</details>

## Q2

Will this code compile ?
```
fn main() {
    let mut a = 7;
    
    let b = &mut a;     

    println!("{}", b);
    *b += 1;
    println!("{}", b);

    println!("{}", a);
    a += 1;
    println!("{}", a);


    println!("{}", b);
    *b += 1;
    println!("{}", b);
}
```

<details>
<summary>Answer :</summary>

 * No

</details>
