<Type Name="WcfCommunicationClient&lt;TServiceContract&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;">
  <TypeSignature Language="C#" Value="public class WcfCommunicationClient&lt;TServiceContract&gt; : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient where TServiceContract : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfCommunicationClient`1&lt;class TServiceContract&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfCommunicationClient(Of TServiceContract)&#xA;Implements ICommunicationClient" />
  <TypeSignature Language="F#" Value="type WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt; = class&#xA;    interface ICommunicationClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TServiceContract">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TServiceContract"><span data-ttu-id="9721d-101">WCF-Dienstvertrags</span><span class="sxs-lookup"><span data-stu-id="9721d-101">WCF service contract</span></span></typeparam>
    <summary>
            <span data-ttu-id="9721d-102">Ein WCF-Client erstellt, indem <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" /> für die Kommunikation mit einem Service Fabric-Dienst mit <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />.</span><span class="sxs-lookup"><span data-stu-id="9721d-102">A WCF client created by <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" /> to communicate with a Service Fabric service using <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Channel">
      <MemberSignature Language="C#" Value="public TServiceContract Channel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TServiceContract Channel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.Channel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Channel As TServiceContract" />
      <MemberSignature Language="F#" Value="member this.Channel : 'ServiceContract" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;.Channel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceContract</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9721d-103">Ruft die WCF-Kanal für den angegebenen Vertrag, den diesen Kommunikationsclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="9721d-103">Gets the WCF channel for the specified contract that this communication client uses.</span></span>
            </summary>
        <value><span data-ttu-id="9721d-104">Der WCF-Kanal für den angegebenen Vertrag, den diesen Kommunikationsclient verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="9721d-104">The WCF channel for the specified contract that this communication client uses.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServiceEndpoint Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServiceEndpoint Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As ResolvedServiceEndpoint" />
      <MemberSignature Language="F#" Value="member this.Endpoint : System.Fabric.ResolvedServiceEndpoint with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;.Endpoint" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.Endpoint</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServiceEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9721d-105">Ruft ab oder legt den Dienstendpunkt, der mit dem der Client verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="9721d-105">Gets or sets the service endpoint to which the client is connected to.</span></span>
            </summary>
        <value><span data-ttu-id="9721d-106">Der Dienstendpunkt, mit dem der Client verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="9721d-106">The service endpoint to which the client is connected to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~WcfCommunicationClient`1 ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="wcfCommunicationClient.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9721d-107">Gibt einem Objekt Gelegenheit zu dem Versuch, Ressourcen freizugeben und andere Bereinigungen durchzuführen, bevor es von der Garbage Collection freigegeben wird.</span><span class="sxs-lookup"><span data-stu-id="9721d-107">Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerName">
      <MemberSignature Language="C#" Value="public string ListenerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.ListenerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenerName As String" />
      <MemberSignature Language="F#" Value="member this.ListenerName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;.ListenerName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ListenerName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9721d-108">Ruft ab oder legt den Namen des Listeners in den dienstreplikats oder die Instanz, die mit dem der Client verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="9721d-108">Gets or sets the name of the listener in the service replica or instance to which the client is connected to.</span></span>
            </summary>
        <value><span data-ttu-id="9721d-109">Der Name des Listeners in den dienstreplikats oder die Instanz, die mit dem der Client verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="9721d-109">The name of the listener in the service replica or instance to which the client is connected to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvedServicePartition">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServicePartition ResolvedServicePartition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServicePartition ResolvedServicePartition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.ResolvedServicePartition" />
      <MemberSignature Language="VB.NET" Value="Public Property ResolvedServicePartition As ResolvedServicePartition" />
      <MemberSignature Language="F#" Value="member this.ResolvedServicePartition : System.Fabric.ResolvedServicePartition with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;.ResolvedServicePartition" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ResolvedServicePartition</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9721d-110">Ruft ab oder legt die aufgelösten Dienstpartition enthält Informationen über die Partition und die Endpunkte, die der Kommunikation mit den dienstreplikats oder die Instanz verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="9721d-110">Gets or sets the resolved service partition which contains information about the partition and the endpoints that can be used to communication with the service replica or instance.</span></span>
            </summary>
        <value><span data-ttu-id="9721d-111">Die aufgelösten Dienstpartition.</span><span class="sxs-lookup"><span data-stu-id="9721d-111">The resolved service partition.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>