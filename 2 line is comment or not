#include<stdio.h>
#include<string.h>
int main()
{
	char input[30];
	int len;
	printf("enter a line of text:");
	scanf("%[^\n]s",input);
	len=strlen(input);
	if(input[0]=='/'&& input[1]=='/')
	{
		printf("single line comment");
	}
	else if(input[0]=='/'&& input[1]=='*' && input[len-1]=='/' && input[len-2]=='*')
	{
			printf("multiline comment");
		}
		else{
			printf("not a comment");
		}
		return 0;

}
