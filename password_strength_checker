import string
def check_password_strength():
    password = input('Enter the password: ')
    strength = 0
    remarks = ''
    lower_count = upper_count = num_count = special_count = 0
    length = len(password)
    for char in password:
        if char in string.ascii_lowercase:
            lower_count += 1
        elif char in string.ascii_uppercase:
            upper_count += 1
        elif char in string.digits:
            num_count += 1
        elif char in string.punctuation:
            special_count += 1
    if lower_count >= 1:
        strength += 1
    else:
        remarks += 'Lowercase letter is missing.\n'
    if upper_count >= 1:
        strength += 1
    else:
        remarks += 'Uppercase letter is missing.\n'
    if num_count >= 1:
        strength += 1
    else:
        remarks += 'Number is missing.\n'
    if length >= 9:
        strength += 1
    else:
        remarks += 'Password length should be at least 9 characters.\n'
    if special_count >= 1:
        strength += 1
    else:
        remarks += 'Special character is missing.\n'
    if strength == 1:
        remarks += 'That\'s a very bad password. Change it as soon as possible.'
    elif strength == 2:
        remarks += 'That\'s a weak password. You should consider using a tougher password.'
    elif strength == 3:
        remarks += 'Your password is okay, but it can be improved.'
    elif strength == 4:
        remarks += 'Your password is hard to guess. But you could make it even more secure.'
    elif strength == 5:
        remarks += 'Now that\'s one hell of a strong password!!! Hackers don\'t have a chance guessing that password!'
    print(f'Password Score: {strength}')
    print(f'Remarks:\n{remarks}')
print('****** Welcome to Password Strength Checker ******')
check_password_strength()
