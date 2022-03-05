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

## Q3

Will this code compile ?
```
fn main() {
    let a = String::from("hello");
    
    let b = a;    

    println!("{}", b);
    b.push('!');
    println!("{}", b);
}
```

<details>
<summary>Answer :</summary>

 * No

</details>

## Q4

Will this code compile ?

```
fn main() {
    let a = String::from("hello");
    
    let mut b = a;    

    println!("{}", b);
    b.push('!');
    println!("{}", b);
}
```

<details>
<summary>Answer :</summary>

 * Yes

</details>

## Q5

Will this code compile ?
```
fn main() {
    let a = String::from("hello");
    
    let mut b = a;    

    println!("{}", b);
    b.push('!');
    println!("{}", b);

    println!("{}", a);
    a.push('!');
    println!("{}", a); 
}
```

<details>
<summary>Answer :</summary>

 * No

</details>

## Q6

Will this code compile ?
```
fn main() {
    let mut a = String::from("hello");
    
    let mut b = a;    

    println!("{}", b);
    b.push('!');
    println!("{}", b);

    println!("{}", a);
    a.push('!');
    println!("{}", a); 
}
```

<details>
<summary>Answer :</summary>

 * No

</details>

