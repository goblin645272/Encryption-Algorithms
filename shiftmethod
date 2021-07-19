def encrypt(text, s):
	result = ""
	# transverse the plain text
	for i in range(len(text)):
		char = text[i]
		# Encrypt uppercase characters in plain text
		if char.isupper():
			result += chr((ord(char) + s-65) % 26 + 65)
		# Encrypt lowercase characters in plain text
		else:
			result += chr((ord(char) + s - 97) % 26 + 97)
	return result


# Check the above function
code = "Goblin"
key = 4
cipher = encrypt(code, key)
print(f"Plain text: {code}")
print(f"Encrypted message: {cipher}")
