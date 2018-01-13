<Type Name="RelayedHttpListenerResponse" FullName="Microsoft.Azure.Relay.RelayedHttpListenerResponse">
  <TypeSignature Language="C#" Value="public sealed class RelayedHttpListenerResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RelayedHttpListenerResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.RelayedHttpListenerResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RelayedHttpListenerResponse" />
  <TypeSignature Language="F#" Value="type RelayedHttpListenerResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Antwort auf eine Anforderung verarbeitet wird, indem ein <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> Objekt.
            Dies ist System.Net.HttpListenerResponse nachgebildet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Net.WebHeaderCollection Headers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.WebHeaderCollection Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerResponse.Headers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Headers As WebHeaderCollection" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Net.WebHeaderCollection" Usage="Microsoft.Azure.Relay.RelayedHttpListenerResponse.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.WebHeaderCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Auflistung von Name/Wert-Paaren für Header, die von diesem Listener zurückgegeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerResponse.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode with get, set" Usage="Microsoft.Azure.Relay.RelayedHttpListenerResponse.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den HTTP-Statuscode an den Client zurückgegeben werden sollen.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Dieses Objekt ist geschlossen.</exception>
        <exception cref="T:System.Net.ProtocolViolationException">Für einen Set-Vorgang angegebene Wert ist ungültig. Gültige Werte liegen zwischen 100 und 999.</exception>
      </Docs>
    </Member>
    <Member MemberName="StatusDescription">
      <MemberSignature Language="C#" Value="public string StatusDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerResponse.StatusDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusDescription As String" />
      <MemberSignature Language="F#" Value="member this.StatusDescription : string with get, set" Usage="Microsoft.Azure.Relay.RelayedHttpListenerResponse.StatusDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt eine textbeschreibung der HTTP-Statuscode an den Client zurückgegeben.</summary>
        <value>Die textbeschreibung der HTTP-Statuscode an den Client zurückgegeben.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Für einen Set-Vorgang angegebene Wert ist null.</exception>
        <exception cref="T:System.ArgumentException">Für einen Set-Vorgang angegebene Wert enthält nicht druckbare Zeichen.</exception>
      </Docs>
    </Member>
  </Members>
</Type>