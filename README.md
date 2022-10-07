# Sample WPF App

This app is a minimum WPF app trying to reproduce the following error:

```
Microsoft.Identity.Client.MsalClientException: 'Unable to load DLL 'msalruntime_x86': The specified module could not be found. (Exception from HRESULT: 0x8007007E) See https://aka.ms/msal-net-wam#troubleshooting'

Inner Exception
DllNotFoundException: Unable to load DLL 'msalruntime_x86': The specified module could not be found. (Exception from HRESULT: 0x8007007E)
```

## Steps to reproduce

1. Clone this repo.
2. Build the solution to restore all nuget packages.
3. Start the project "WPF.Package".