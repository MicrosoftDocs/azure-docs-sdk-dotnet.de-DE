<Type Name="WcfActorServiceRemotingListener" FullName="Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class WcfActorServiceRemotingListener : Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfActorServiceRemotingListener extends Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfActorServiceRemotingListener&#xA;Inherits WcfServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type WcfActorServiceRemotingListener = class&#xA;    inherit WcfServiceRemotingListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b3945-101">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> , verwendet Windows Communication Foundation-actordienste Schnittstelle Remoting bereit.</span><span class="sxs-lookup"><span data-stu-id="b3945-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> that uses Windows Communication Foundation to provide interface remoting for actor services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, System.ServiceModel.Channels.Binding listenerBinding = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, class System.ServiceModel.Channels.Binding listenerBinding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener.#ctor(Microsoft.ServiceFabric.Actors.Runtime.ActorService,System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService * System.ServiceModel.Channels.Binding -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener (actorService, listenerBinding)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="actorService"><span data-ttu-id="b3945-102">Der Akteur-Dienst.</span><span class="sxs-lookup"><span data-stu-id="b3945-102">The actor service.</span></span></param>
        <param name="listenerBinding"><span data-ttu-id="b3945-103">WCF-Bindung für den Listener verwendet.</span><span class="sxs-lookup"><span data-stu-id="b3945-103">WCF binding to use for the listener.</span></span> <span data-ttu-id="b3945-104">Wenn der Listener, der Bindung nicht angegeben ist oder null, ein Standardlistener, die Bindung wird mithilfe der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode erstellt eine <see cref="T:System.ServiceModel.NetTcpBinding" /> ohne Sicherheit.</span><span class="sxs-lookup"><span data-stu-id="b3945-104">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method which creates a <see cref="T:System.ServiceModel.NetTcpBinding" /> with no security.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3945-105">Erstellt einen WCF basiert Akteur Remoting Listener.</span><span class="sxs-lookup"><span data-stu-id="b3945-105">Constructs a WCF based actor remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler serviceRemotingMessageHandler, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler serviceRemotingMessageHandler, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Runtime.WcfActorServiceRemotingListener (serviceContext, serviceRemotingMessageHandler, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceRemotingMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="b3945-106">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="b3945-106">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="serviceRemotingMessageHandler"><span data-ttu-id="b3945-107">Der Handler für das empfangen und Verarbeiten von Nachrichten von Remoting.</span><span class="sxs-lookup"><span data-stu-id="b3945-107">The handler for receiving and processing remoting messages.</span></span> <span data-ttu-id="b3945-108">Beim Empfangen von Nachrichten übermittelt der Listener die Nachrichten an den Handler.</span><span class="sxs-lookup"><span data-stu-id="b3945-108">As the messages are received the listener delivers the messages to the handler.</span></span>
            </param>
        <param name="listenerBinding"><span data-ttu-id="b3945-109">WCF-Bindung für den Listener verwendet.</span><span class="sxs-lookup"><span data-stu-id="b3945-109">WCF binding to use for the listener.</span></span> <span data-ttu-id="b3945-110">Wenn der Listener, der Bindung nicht angegeben ist oder null, ein Standardlistener, die Bindung wird mithilfe der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="b3945-110">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
            </param>
        <param name="address"><span data-ttu-id="b3945-111">Die Endpunktadresse für den WCF-Listener verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b3945-111">The endpoint address to use for the WCF listener.</span></span> <span data-ttu-id="b3945-112">Wenn dies nicht der angegebenen "oder" null ", die Endpunktadresse wird erstellt unter Verwendung der Standard-Endpunkt-Ressource mit dem Namen"ServiceEndpoint"in das Manifest definiert.</span><span class="sxs-lookup"><span data-stu-id="b3945-112">If not specified or null, the endpoint address is created using the default endpoint resource named "ServiceEndpoint" defined in the service manifest.</span></span> 
            </param>
        <summary>
            <span data-ttu-id="b3945-113">Ein WCF-Konstrukte basierend Dienst Remoting Listener.</span><span class="sxs-lookup"><span data-stu-id="b3945-113">Constructs a WCF based service remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>