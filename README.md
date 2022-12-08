## Poor Name
1. Mysterious Names
 - e.g - let od, let page1 , function button_Click1() etc
1. Meaningless Names
 - BeginCheckFunctionality_StoreClientSideCheckboxIDsArray();
1. Name with Encodings
 - let iMaxRequests --> maxRequests
 - var m_objCollection = new StringCollection();
1. countryNames
1. Ambiguous Names
 - let incidentNameID; -> Nullable Variable -> How can an ID be nullable
1. Noisy Names
 - theCustomer:Customer --> customer
 - ListOfApprovedCustomers:List<Customer> --> approvedCustomers
1. Use ReSharper
 - Select variable name --> F2 --> rename --> Enter

# Names
## Not too short, not too long
1. Meaningful
1. Reveal Intention
1. Choose from problem domain


# Inconsistent Naming Conventions
## Bad Practice
    - GetCustomer(_id);
    - saveCustomer(Customer);
    - private customerId;
    - PascalCase, camelCase
## Actual Naming Conventions
    - PascalCase - ClassName,Properties,Methods
    - camelCase - privateProperty,functionParmaters,localVariables. - Use PrivateVariables - _id;

# Poor Method Signatures
    - GetCustomer(airplane:number):Orange
    - Parse(command:number):void --> Parse(command:String):number

- ctrl+shift+r --> select option --> safe delete --> comfirm it
- ctrl+w --> select block of codes --> ctrl+shift+r --> Extract Method --> Enter -->Select option
--> Next
- ctrl+shift+w --> If over selected codes


# Method Signatures
-- Check the return types
-- Check the method name
-- Check the parameters

# Long Parameter List
## Method Parameters Best Practices
    - Less than 3 parameters
# Output Parameters
    - Avoid them!
    - Return an object from a method instead.
# Variable Declarations on the top
    - Declare them close to their usage.
# Magic Numbers
## Avoid Magic Numbers
    - Avoid using 1 , 2 , 3 etc
    - Instead use constants (Single Usage) or enums (Multiple Usage).
# Nested Conditionals
    - Avoid them!
# Switch Statements
## Open Close Principle
    - Open for extension -- Change features of app by adding classes , functions and codes
    - Close for modification -- Change app features by not modifying previous codes.
    - Replace them with polymorphic dispatch
    - Use Push Member Down refactoring
# Duplicated Codes
    - Use Dry
# Comments
    - Only write comments to explain whys and hows not what.
    - Don't write comments, re-write your code!
    - Don't explain "Whats" (the obvious)
    - Explain "whys" and "hows"
    - Whenever ou comment that mean you to explain your code.
# Long Methods
    - Methods Should be Shorts (less than 10 lines)
    - Methods Should do only one thing.

- Write Code , methods and class as Newspaper Story
- Also align them as a story in the newspaper.
