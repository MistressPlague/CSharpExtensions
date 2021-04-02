# CSharpExtensions
A Bunch Of Very Useful Extension Methods, All In One Useful Class.

# What Is In This?
Method Name | Function
------------ | -------------
GetFromTo<T>(this List<T> list, int from, int to) | Retrieves All Items In A List Starting From **from** To **to** - Useful For Making Pages From A List
MakeAlphaNumeric(this string input, params char[] exceptions) | Effectively Sanitizes A String To AlphaNumeric - You Can Define Some Exceptions To Allow Past The Sanitization
MultilineContainsExactTextToLower(this string multilineinput, string containsthis) | Checks A Multiline String For Exact Text You Define - Check In Lowercase
ToRgb(this Color color) | Converts A System.Drawing.Color To RGB In Int Form - Simple Append A "#" Before This In A String For The Pure Hex.
IsTermFullyDefined(this string text, string term, int expectedLength, string[] disallowedText) | Checks If A Term Is Fully Defined In A String - Such As Say You Have A Log Which Shows A User ID, You Can Use This To See If There's A User ID Actually There, Or It Is Empty.
ReplaceLast(this string Source, string oldChar, string newChar) | Replaces The Last Occurance Of A String
GetTextAfter(this string sourceString, string getTextAfterThis, int lengthOfWhatToGetAfterPrevString = 90000) | Retrieves All Text After A Specified Term To The End Of The Entire String Or To Your Specified Length
GetToEndOfLine(this string sourceString) | Gets ALL Text In A String To The First NewLine
ContainsAllOf(this string input, string[] terms) | Checks If All Of The Terms You Define Are In A String
ConvertToString(this byte[] array) | Converts A byte[] To A String
ReplaceAtIndex(this string Source, string oldChar, string newChar, int indexJustBeforeoldChar) | Replaces Text ONLY At The Specified Starting Index - Use This As A Safe Replace Method
