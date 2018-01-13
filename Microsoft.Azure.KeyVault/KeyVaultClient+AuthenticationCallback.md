<Type Name="KeyVaultClient+AuthenticationCallback" FullName="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback">
  <TypeSignature Language="C#" Value="public delegate System.Threading.Tasks.Task&lt;string&gt; KeyVaultClient.AuthenticationCallback(string authority, string resource, string scope);" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed KeyVaultClient/AuthenticationCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function KeyVaultClient.AuthenticationCallback(authority As String, resource As String, scope As String) As Task(Of String) " />
  <TypeSignature Language="F#" Value="type KeyVaultClient.AuthenticationCallback = delegate of string * string * string -&gt; Task&lt;string&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="authority" Type="System.String" />
    <Parameter Name="resource" Type="System.String" />
    <Parameter Name="scope" Type="System.String" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="authority"> Der Bezeichner der Autorisierungsstelle, eine URL. </param>
    <param name="resource"> Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens, eine URL ist. </param>
    <param name="scope"> Der Bereich der Authentifizierungsanforderung. </param>
    <summary>
            Die Authentifizierung Rückrufdelegat also von der Clientcode implementiert werden muss
            </summary>
    <returns> Zugriffstoken </returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>