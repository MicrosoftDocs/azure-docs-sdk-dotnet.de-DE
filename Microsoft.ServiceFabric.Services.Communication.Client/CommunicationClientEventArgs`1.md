<Type Name="CommunicationClientEventArgs&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public class CommunicationClientEventArgs&lt;TCommunicationClient&gt; : EventArgs where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CommunicationClientEventArgs`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1" />
  <TypeSignature Language="VB.NET" Value="Public Class CommunicationClientEventArgs(Of TCommunicationClient)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type CommunicationClientEventArgs&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TCommunicationClient">
      <Constraints>
        <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TCommunicationClient">Kommunikation-Clienttyp</typeparam>
    <summary>
            Gibt die Argumente für die Kommunikation von Client verbunden/getrennt Ereignisse-Handler.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CommunicationClientEventArgs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Client">
      <MemberSignature Language="C#" Value="public TCommunicationClient Client { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TCommunicationClient Client" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1.Client" />
      <MemberSignature Language="VB.NET" Value="Public Property Client As TCommunicationClient" />
      <MemberSignature Language="F#" Value="member this.Client : 'CommunicationClient with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.Client" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TCommunicationClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Kommunikationsclient für die das Ereignis ausgelöst wird.
            </summary>
        <value>Kommunikationsclient</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>