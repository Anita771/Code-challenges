# Code-challenges
# First Code challenge 
# Create an if statement that tells if a phone number is in international format (starts with a plus character)

function test (phoneNumber) {
  if (phoneNumber[0]=== '+')
    {return 'known';
    }
    else {
        return 'unknown';
        }
         }
   console.log ((test('+77228'); // print known
   console.log ((test('-77228'); // print unknown
   console.log ((test('77228');  // print unknown
   
