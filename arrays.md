# Arrays

### Passing 2-D array to function

```cpp
void foo(int *arr,int row,int col)
{
	for(int i=0;i<row;i++)
	{
		for(int j=0;j<col;j++)
			cout<<arr[i*row + j]<<" ";
	}
}
//don't forgot to typecast into double pointer before passing actual arguement
int main()
{
int a[r][c];
foo((int*)a,r,c);
}
```

