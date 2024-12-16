char* convertToTitle(int columnNumber) {
    static char str[10];   
    int i = 0;
 
    while (columnNumber > 0) {
        columnNumber--;   
        str[i] = (char)(columnNumber % 26 + 'A');   
        columnNumber /= 26;  
        i++;
    }
    
str[i] = '\0';    
    for (int j = 0; j < i / 2; j++) {
        char temp = str[j];
        str[j] = str[i - j - 1];
        str[i - j - 1] = temp;
    }
      return str; 
}
