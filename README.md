# GrayscaleGroup
Grayscale effect in unity like CanvasGroup

## Features
- Easy to use
- A lite API (field `GrayscaleInGroup` control all of child group)
- TextMeshProUGUI shader prepare to ready

## How to install
### Git Installation or Copy to project

## Usage
### How to enable Grayscale

```csharp
using UnityEngine;
using Binaryinject;

public class Test : MonoBehaviour
{
	[SerializeField] private GrayscaleGroup _group = null;
	
	private void Awake()
	{
		_group.GrayscaleInGroup = true;
	}
}
```



