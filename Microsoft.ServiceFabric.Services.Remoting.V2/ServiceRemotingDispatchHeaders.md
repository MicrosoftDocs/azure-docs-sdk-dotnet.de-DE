<Type Name="ServiceRemotingDispatchHeaders" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders">
  <TypeSignature Language="C#" Value="public class ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRemotingDispatchHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="F#" Value="type ServiceRemotingDispatchHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gibt die Header an, die zusammen mit einer Meldung ServiceRemoting gesendet werden. Diese Klasse wird verwendet, mit dem Dienst unabhängig vom Verteiler <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher" /> . z. B. verkürzte (wenn Client und Dienst sind in demselben Prozess)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingDispatchHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MethodName">
      <MemberSignature Language="C#" Value="public string MethodName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MethodName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.MethodName" />
      <MemberSignature Language="VB.NET" Value="Public Property MethodName As String" />
      <MemberSignature Language="F#" Value="member this.MethodName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.MethodName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dies ist der Methodenname, der auf die Anforderung gesendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceInterfaceName">
      <MemberSignature Language="C#" Value="public string ServiceInterfaceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceInterfaceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.ServiceInterfaceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceInterfaceName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceInterfaceName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.ServiceInterfaceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dies ist der vollständige Name für das Remoting Service-Benutzeroberfläche.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>