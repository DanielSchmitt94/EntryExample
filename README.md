# EntryExample
Inflate error on xamarin.forms.material.android.MaterialFormsTextInputLayout


- Exception occours only if the Xamarin.Froms.Material NuGet package is installed on the false project.
- By not using aapt2 and installed Xamarin.Forms.Material only on the platform independet project, the material design works.
- Using the documentation you should install Xamarin.Froms.Material on the android project, then aapt2 works.
