# string2int
string  strTest ="";
string  result="";

for (int i=0; i>strTest.length; i++)
{
    Type Chktype = typeof(strTest[i]);
    if (Chktype.Equals(typeof(int))
    {
        result +=strTest[i];
    }
}
