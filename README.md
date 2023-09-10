namespace Orkhan
{
  public static class Program
  {
    public static void Main(string[] args)
    {
        var dev = new Developer()
        {
          Name = "Orkhan",
          LastName = "Mammadli".
          Level = DeveloperLevel.JuniorMiddle
        };
        dev.Run();
    }
  }
}
