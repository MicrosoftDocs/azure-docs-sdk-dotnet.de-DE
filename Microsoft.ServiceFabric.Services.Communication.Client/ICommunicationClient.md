<Type Name="ICommunicationClient" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient">
  <TypeSignature Language="C#" Value="public interface ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICommunicationClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICommunicationClient" />
  <TypeSignature Language="F#" Value="type ICommunicationClient = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Definiert die Schnittstelle, die die Kommunikation zwischen Client für zuverlässige Dienste darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServiceEndpoint Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServiceEndpoint Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As ResolvedServiceEndpoint" />
      <MemberSignature Language="F#" Value="member this.Endpoint : System.Fabric.ResolvedServiceEndpoint with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServiceEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Dienstendpunkt, der mit dem der Client verbunden ist.
            </summary>
        <value>
          <see cref="T:System.Fabric.ResolvedServiceEndpoint" />
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerName">
      <MemberSignature Language="C#" Value="public string ListenerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ListenerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenerName As String" />
      <MemberSignature Language="F#" Value="member this.ListenerName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ListenerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Listeners in das Replikat oder eine Instanz mit dem der Client verbunden ist.
            </summary>
        <value>Name des Listeners</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvedServicePartition">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServicePartition ResolvedServicePartition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServicePartition ResolvedServicePartition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ResolvedServicePartition" />
      <MemberSignature Language="VB.NET" Value="Public Property ResolvedServicePartition As ResolvedServicePartition" />
      <MemberSignature Language="F#" Value="member this.ResolvedServicePartition : System.Fabric.ResolvedServicePartition with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ResolvedServicePartition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Dienstpartition gelöst, der Zeitpunkt der Erstellung dieser Client verwendet wurde.
            </summary>
        <value>
          <see cref="T:System.Fabric.ResolvedServicePartition" />-Objekt</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>