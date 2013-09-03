# Letter Casing in Go

Letter casing functions are available in the core `strings` package and always
have Unicode semantics.

    lowercase = strings.ToLower(str)
    uppercase = strings.ToUpper(str)
    titlecase = strings.ToTitle(str)  // every character
    titlecase = strings.Title(str)    // first character of each word

Although there is no case folding function for strings, there is a caseless
equality function that uses case folding, 

    strings.EqualFold(str1, str2)
