# ComapreObjects
Include this class library in your solution and you can call it like this
 ```
 public Dictionary<string, string> GetObjectDifferences(Object1 obj1, Object2 obj2)
        {
            var differences = new Dictionary<string, string>();
            CompareHelper.CompareObjects(obj1, obj2, ref differences);
            return differences;
        }
