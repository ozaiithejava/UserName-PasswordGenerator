# UserName-PasswordGenerator
a basic username and passaword generator


**Kullanım**

maine yapıştırın bunu

        int nameLength = 8; // isim uzunlugu
        int passwordLength = 12; // şif uzunlugu

        String randomName = PasswordGenerator.generateRandomName(nameLength);
        String randomPassword = PasswordGenerator.generateRandomPassword(passwordLength);

        System.out.println("Random Name: " + randomName);
        System.out.println("Random Password: " + randomPassword);
