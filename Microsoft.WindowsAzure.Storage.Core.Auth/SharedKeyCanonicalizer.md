<Type Name="SharedKeyCanonicalizer" FullName="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer">
  <TypeSignature Language="C#" Value="public sealed class SharedKeyCanonicalizer : Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedKeyCanonicalizer extends System.Object implements class Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedKeyCanonicalizer&#xA;Implements ICanonicalizer" />
  <TypeSignature Language="F#" Value="type SharedKeyCanonicalizer = class&#xA;    interface ICanonicalizer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine Canonicalizer, die HTTP-Anforderungsdaten in ein Standardformat für das Signieren über das Shared Key-Authentifizierungsschema für den BLOB- oder Warteschlangendienst konvertiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizationScheme">
      <MemberSignature Language="C#" Value="public string AuthorizationScheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.AuthorizationScheme" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationScheme As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationScheme : string" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.AuthorizationScheme" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.AuthorizationScheme</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die für die Kanonikalisierung verwendete Authentifizierungsschema ab.
            </summary>
        <value>Für die Kanonikalisierung verwendete Autorisierungsschemas.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizeHttpRequest">
      <MemberSignature Language="C#" Value="public string CanonicalizeHttpRequest (System.Net.HttpWebRequest request, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CanonicalizeHttpRequest(class System.Net.HttpWebRequest request, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CanonicalizeHttpRequest (request As HttpWebRequest, accountName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string&#xA;override this.CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string" Usage="sharedKeyCanonicalizer.CanonicalizeHttpRequest (request, accountName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request">Die HTTP-Anforderung, die signiert werden muss.</param>
        <param name="accountName">Der Name des Speicherkontos an, dem die HTTP-Anforderung zugreifen.</param>
        <summary>
            Konvertiert die angegebene HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden an.
            </summary>
        <returns>Die kanonikalisierte Zeichenfolge, die die HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Instance">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer Instance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer Instance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.Instance" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Instance As SharedKeyCanonicalizer" />
      <MemberSignature Language="F#" Value="member this.Instance : Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.Instance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine statische Instanz die <see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer" /> Objekt.
            </summary>
        <value>Die statische Instanz der Klasse.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>