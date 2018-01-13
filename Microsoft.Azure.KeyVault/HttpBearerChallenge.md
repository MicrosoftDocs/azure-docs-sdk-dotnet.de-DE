<Type Name="HttpBearerChallenge" FullName="Microsoft.Azure.KeyVault.HttpBearerChallenge">
  <TypeSignature Language="C#" Value="public sealed class HttpBearerChallenge" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HttpBearerChallenge extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.HttpBearerChallenge" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HttpBearerChallenge" />
  <TypeSignature Language="F#" Value="type HttpBearerChallenge = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Verarbeitet HTTP-trägertoken Challenge-Vorgänge
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpBearerChallenge (Uri requestUri, string challenge);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri requestUri, string challenge) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallenge.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (requestUri As Uri, challenge As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.HttpBearerChallenge : Uri * string -&gt; Microsoft.Azure.KeyVault.HttpBearerChallenge" Usage="new Microsoft.Azure.KeyVault.HttpBearerChallenge (requestUri, challenge)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestUri" Type="System.Uri" />
        <Parameter Name="challenge" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="requestUri">To be added.</param>
        <param name="challenge">Die AuthenticationHeaderValue, analysieren</param>
        <summary>
            Analysiert eine HTTP-WWW-Authentifizierung Träger Herausforderung von einem Server an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationServer">
      <MemberSignature Language="C#" Value="public string AuthorizationServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.AuthorizationServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationServer As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationServer : string" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.AuthorizationServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt den URI für den autorisierungsserver, falls vorhanden, andernfalls eine Zeichenfolge. Leere
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBearerChallenge">
      <MemberSignature Language="C#" Value="public static bool IsBearerChallenge (string challenge);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsBearerChallenge(string challenge) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallenge.IsBearerChallenge(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsBearerChallenge (challenge As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsBearerChallenge : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.IsBearerChallenge challenge" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="challenge" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="challenge">Die AuthenticationHeaderValue testen</param>
        <summary>
            Testet, ob ein Authentifizierungsheader Träger schwierig ist
            </summary>
        <returns>"True", wenn der Header Träger schwierig ist.</returns>
        <remarks>
            Diese Methode ist auferlegt: Wenn der Parameter null ist, oder das Schema im Header nicht vorhanden ist, und klicken Sie dann einfach "false" zurückgegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.Resource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt der Bereich-Wert, wenn vorhanden ist, andernfalls die Autorität für die Anforderungs-URI, die im Konstruktor angegebenen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public string Scope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.Scope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scope As String" />
      <MemberSignature Language="F#" Value="member this.Scope : string" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt die Bereichswert, falls vorhanden, andernfalls Zeichenfolge zurück. Leere
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAuthority">
      <MemberSignature Language="C#" Value="public string SourceAuthority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.SourceAuthority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceAuthority As String" />
      <MemberSignature Language="F#" Value="member this.SourceAuthority : string" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.SourceAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Autorität für die Anforderungs-URI
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceUri">
      <MemberSignature Language="C#" Value="public Uri SourceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.SourceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceUri As Uri" />
      <MemberSignature Language="F#" Value="member this.SourceUri : Uri" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.SourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Quell-URI
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public bool TryGetValue (string key, out string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetValue(string key, [out] string&amp; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallenge.TryGetValue(System.String,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValue (key As String, ByRef value As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetValue : string *  -&gt; bool" Usage="httpBearerChallenge.TryGetValue (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key">Der Schlüssel abgerufen werden sollen</param>
        <param name="value">Der Wert für den angegebenen Schlüssel</param>
        <summary>
            Gibt den Wert am angegebenen Schlüssel gespeichert.
            </summary>
        <returns>"True", wenn der Schlüssel gefunden wurde, false ist, wenn es nicht</returns>
        <remarks>
            Wenn der Schlüssel nicht vorhanden ist, wird "false" zurückgeben, und der Inhalt der Wert nicht geändert
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>