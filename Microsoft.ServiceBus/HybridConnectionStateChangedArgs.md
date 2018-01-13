<Type Name="HybridConnectionStateChangedArgs" FullName="Microsoft.ServiceBus.HybridConnectionStateChangedArgs">
  <TypeSignature Language="C#" Value="public class HybridConnectionStateChangedArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionStateChangedArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.HybridConnectionStateChangedArgs" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionStateChangedArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type HybridConnectionStateChangedArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die Argumente für die statusänderung der Hybrid-Verbindung dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionStateChangedArgs (Microsoft.ServiceBus.HybridConnectionState state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.HybridConnectionState state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HybridConnectionStateChangedArgs.#ctor(Microsoft.ServiceBus.HybridConnectionState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As HybridConnectionState)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.HybridConnectionStateChangedArgs : Microsoft.ServiceBus.HybridConnectionState -&gt; Microsoft.ServiceBus.HybridConnectionStateChangedArgs" Usage="new Microsoft.ServiceBus.HybridConnectionStateChangedArgs state" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.ServiceBus.HybridConnectionState" />
      </Parameters>
      <Docs>
        <param name="state">Der Status der hybridverbindung.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.HybridConnectionStateChangedArgs" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionState">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.HybridConnectionState ConnectionState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.HybridConnectionState ConnectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HybridConnectionStateChangedArgs.ConnectionState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionState As HybridConnectionState" />
      <MemberSignature Language="F#" Value="member this.ConnectionState : Microsoft.ServiceBus.HybridConnectionState" Usage="Microsoft.ServiceBus.HybridConnectionStateChangedArgs.ConnectionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HybridConnectionState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den aktuellen Verbindungsstatus der hybridverbindung ab.</summary>
        <value>Gibt <see cref="T:Microsoft.ServiceBus.HybridConnectionState" />. Enthält den Verbindungsstatus. </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>