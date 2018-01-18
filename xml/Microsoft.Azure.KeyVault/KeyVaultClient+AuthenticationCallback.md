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
    <param name="authority"> <span data-ttu-id="64fc9-101">Der Bezeichner der Autorisierungsstelle, eine URL.</span><span class="sxs-lookup"><span data-stu-id="64fc9-101">Identifier of the authority, a URL.</span></span> </param>
    <param name="resource"> <span data-ttu-id="64fc9-102">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens, eine URL ist.</span><span class="sxs-lookup"><span data-stu-id="64fc9-102">Identifier of the target resource that is the recipient of the requested token, a URL.</span></span> </param>
    <param name="scope"> <span data-ttu-id="64fc9-103">Der Bereich der Authentifizierungsanforderung.</span><span class="sxs-lookup"><span data-stu-id="64fc9-103">The scope of the authentication request.</span></span> </param>
    <summary>
            <span data-ttu-id="64fc9-104">Die Authentifizierung Rückrufdelegat also von der Clientcode implementiert werden muss</span><span class="sxs-lookup"><span data-stu-id="64fc9-104">The authentication callback delegate which is to be implemented by the client code</span></span>
            </summary>
    <returns> <span data-ttu-id="64fc9-105">Zugriffstoken</span><span class="sxs-lookup"><span data-stu-id="64fc9-105">access token</span></span> </returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>