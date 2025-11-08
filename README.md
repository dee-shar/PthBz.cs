# PthBz.cs
Web-API for [pth.bz](https://pth.bz) an free URL Shortener service with Permanent 301 Redirects

## Example
```cs
using PthBzApi;

namespace Application
{
    internal class Program
    {
        static async Task Main()
        {
            var api = new PthBz();
            string url = await api.ShortenUrl("https://google.com");
            Console.WriteLine(url);
        }
    }
}
```
