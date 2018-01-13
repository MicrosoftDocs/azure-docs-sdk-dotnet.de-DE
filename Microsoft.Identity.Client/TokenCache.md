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
            Tokencache-Klasse, die von ConfidentialClientApplication und PublicClientApplication Zugriff speichern und Aktualisieren von Token verwendet.
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
            Ruft ab oder legt das Flag, das angibt, ob der Cachestatus geändert wurde.
            MSAL Methoden legen Sie dieses Flag nach jeder Änderung.
            Anwendung der Aufrufer sollte das Flag nach dem Serialisieren und Beibehalten des Zustands des Caches zurückgesetzt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>