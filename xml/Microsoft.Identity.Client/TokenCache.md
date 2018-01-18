<Type Name="TokenCache" FullName="Microsoft.Identity.Client.TokenCache">
  <TypeSignature Language="C#" Value="public sealed class TokenCache" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TokenCache extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.TokenCache" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TokenCache" />
  <TypeSignature Language="F#" Value="type TokenCache = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b774a-101">Tokencache-Klasse, die von ConfidentialClientApplication und PublicClientApplication Zugriff speichern und Aktualisieren von Token verwendet.</span><span class="sxs-lookup"><span data-stu-id="b774a-101">Token cache class used by ConfidentialClientApplication and PublicClientApplication to store access and refresh tokens.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenCache ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.TokenCache.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasStateChanged">
      <MemberSignature Language="C#" Value="public bool HasStateChanged { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasStateChanged" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.TokenCache.HasStateChanged" />
      <MemberSignature Language="VB.NET" Value="Public Property HasStateChanged As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasStateChanged : bool with get, set" Usage="Microsoft.Identity.Client.TokenCache.HasStateChanged" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b774a-102">Ruft ab oder legt das Flag, das angibt, ob der Cachestatus geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b774a-102">Gets or sets the flag indicating whether cache state has changed.</span></span>
            <span data-ttu-id="b774a-103">MSAL Methoden legen Sie dieses Flag nach jeder Änderung.</span><span class="sxs-lookup"><span data-stu-id="b774a-103">MSAL methods set this flag after any change.</span></span>
            <span data-ttu-id="b774a-104">Anwendung der Aufrufer sollte das Flag nach dem Serialisieren und Beibehalten des Zustands des Caches zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="b774a-104">Caller application should reset the flag after serializing and persisting the state of the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>