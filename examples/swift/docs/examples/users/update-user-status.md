/// Swift Appwrite SDK
/// Produced by Appwrite SDK Generator
///

var client: Client = Client()

client
    .setProject('')
;

users: Users =  Users(client);

result = users.updateUserStatus("[USER_ID]", "1");