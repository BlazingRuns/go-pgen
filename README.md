# Pgen

Password Generator Written in golang

-- Main --


func main() {
	rand.Seed(time.Now().Unix())
	minSpecialChar := 1
	minNum := 1
	minUpperCase := 1
	passwordLength := 12
	password := generatePassword(passwordLength, minSpecialChar, minNum, minUpperCase)
	fmt.Println(password)
}

-- Main --

------------------------------------------------------------------
This will generate passwords and choose the settings you desire
------------------------------------------------------------------

2020 @blazing_runs
