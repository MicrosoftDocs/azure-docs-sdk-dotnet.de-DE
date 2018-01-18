<Type Name="FabricTransportServiceRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingProviderAttribute : Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingProviderAttribute extends Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportServiceRemotingProviderAttribute&#xA;Inherits ServiceRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type FabricTransportServiceRemotingProviderAttribute = class&#xA;    inherit ServiceRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="9af77-101">Legt den Fabric-TCP-Transport als Standard-Remoting Transport Dienstanbieter in der Assembly fest.</span><span class="sxs-lookup"><span data-stu-id="9af77-101">Sets Fabric TCP transport as the default service remoting transport provider in the assembly.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9af77-102">Erstellt eine <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" /> die festzulegende Fabric-TCP-Transport als Standard-Remoting Transport Dienstanbieter in der Assembly verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="9af77-102">Constructs a <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" /> which can be used to set Fabric TCP transport as the default service remoting transport provider in the assembly.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public long ConnectTimeoutInMilliseconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectTimeoutInMilliseconds As Long" />
      <MemberSignature Language="F#" Value="member this.ConnectTimeoutInMilliseconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="9af77-103">Ruft ab oder legt die Connect Timeout in Millisekunden.</span><span class="sxs-lookup"><span data-stu-id="9af77-103">Gets or Sets the connect timeout in milliseconds.</span></span> <span data-ttu-id="9af77-104">Diese Einstellung gibt die maximale Zeitspanne für die Verbindung eingerichtet werden kann.</span><span class="sxs-lookup"><span data-stu-id="9af77-104">This settings specifies the maximum time allowed for the connection to be established.</span></span>
                </summary>
        <value>
                <span data-ttu-id="9af77-105">Das Connect Timeout in Millisekunden.</span><span class="sxs-lookup"><span data-stu-id="9af77-105">The connect timeout in Milliseconds.</span></span>
            </value>
        <remarks><span data-ttu-id="9af77-106">Standardwert für ConnectTimeout-Timeout beträgt 5 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="9af77-106">Default Value for ConnectTimeout Timeout is 5 seconds.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">
               <span data-ttu-id="9af77-107">Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="9af77-107">The client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="9af77-108">Erstellt eine Factory V1 Dienst Remoting Client zum Herstellen einer Verbindung mit dem Dienst über Remote Dienstschnittstellen.</span><span class="sxs-lookup"><span data-stu-id="9af77-108">Creates a  V1 service remoting client factory for connecting to the service over remoted service interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="9af77-109">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> , die verwendet werden kann, mit <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> Dienstproxy zu wenden Sie sich an einen Dienst zustandslose oder zustandsbehaftete über Remote Akteur-Schnittstelle generiert.</span><span class="sxs-lookup"><span data-stu-id="9af77-109">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> that can be used with <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> to generate service proxy to talk to a stateless or stateful service over remoted actor interface.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">
               <span data-ttu-id="9af77-110">Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="9af77-110">The client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="9af77-111">Erstellt eine Factory V2 Dienst Remoting Client zum Herstellen einer Verbindung mit dem Dienst über Remote Dienstschnittstellen.</span><span class="sxs-lookup"><span data-stu-id="9af77-111">Creates a  V2 service remoting client factory for connecting to the service over remoted service interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="9af77-112">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> , die verwendet werden kann, mit <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> Dienstproxy zu wenden Sie sich an einen Dienst zustandslose oder zustandsbehaftete über Remote Akteur-Schnittstelle generiert.</span><span class="sxs-lookup"><span data-stu-id="9af77-112">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> that can be used with <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> to generate service proxy to talk to a stateless or stateful service over remoted actor interface.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListener(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="9af77-113">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="9af77-113">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="serviceImplementation">
                <span data-ttu-id="9af77-114">Das Dienstobjekt für die Implementierung.</span><span class="sxs-lookup"><span data-stu-id="9af77-114">The service implementation object.</span></span>
            </param>
        <summary>
                <span data-ttu-id="9af77-115">Erstellt einen Dienst Remoting-Listener für das Remoting Dienstschnittstelle an.</span><span class="sxs-lookup"><span data-stu-id="9af77-115">Creates a service remoting listener for remoting the service interface.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="9af77-116">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für die angegebene dienstimplementierung.</span><span class="sxs-lookup"><span data-stu-id="9af77-116">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified service implementation.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2 (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="9af77-117">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="9af77-117">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="serviceImplementation">
                <span data-ttu-id="9af77-118">Das Dienstobjekt für die Implementierung.</span><span class="sxs-lookup"><span data-stu-id="9af77-118">The service implementation object.</span></span>
            </param>
        <summary>
                <span data-ttu-id="9af77-119">Erstellt einen V2 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="9af77-119">Creates a V2 service remoting listener for remoting the service interface.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="9af77-120">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für die angegebene dienstimplementierung.</span><span class="sxs-lookup"><span data-stu-id="9af77-120">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" /> as <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified service implementation.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long KeepAliveTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="9af77-121">Ruft ab oder legt das Keep-alive-Timeout in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="9af77-121">Gets or Sets the keep alive timeout in seconds.</span></span> <span data-ttu-id="9af77-122">Diese Einstellung ist hilfreich, wenn Client und Dienst über Lastenausgleich verbunden sind, die die Verbindung geschlossen wird, wenn es einige Zeit im Leerlauf befunden hat.</span><span class="sxs-lookup"><span data-stu-id="9af77-122">This settings is useful in the scenario when the client and service are connected via load balancer that closes the connection if it is idle for some time.</span></span>
                <span data-ttu-id="9af77-123">Wenn Keep-alive-Timeout konfiguriert ist, die Verbindung aktiv bleiben per Ping-Nachrichten in diesem Intervall.</span><span class="sxs-lookup"><span data-stu-id="9af77-123">If keep alive timeout is configured, the connection will be kept alive by sending ping messages at that interval.</span></span>
                </summary>
        <value>
                <span data-ttu-id="9af77-124">Die Keep-alive-Timeout in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="9af77-124">The keep alive timeout in seconds.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="9af77-125">Ruft ab oder legt die maximale Größe der Remoting-Nachricht in Bytes fest.</span><span class="sxs-lookup"><span data-stu-id="9af77-125">Gets or Sets the maximum size of the remoting message in bytes.</span></span>
                <span data-ttu-id="9af77-126">Wenn kein Wert für diese Eigenschaft angegeben wird, oder es ist kleiner als oder gleich 0 (null), einen Standardwert von 4,194,304 Bytes (4 MB) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="9af77-126">If value for this property is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
                </summary>
        <value>
                <span data-ttu-id="9af77-127">Die maximale Größe der Remoting Nachricht in Bytes.</span><span class="sxs-lookup"><span data-stu-id="9af77-127">The maximum size of the remoting message in bytes.</span></span> <span data-ttu-id="9af77-128">Wenn dieser Wert nicht angegeben ist, oder es ist kleiner als oder gleich 0 (null), einen Standardwert von 4,194,304 Bytes (4 MB) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="9af77-128">If this value is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long OperationTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OperationTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OperationTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="9af77-129">Ruft ab oder legt die Zeitüberschreitung in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="9af77-129">Gets or Sets the operation timeout in seconds.</span></span> <span data-ttu-id="9af77-130">Wenn der Vorgang nicht in der angegebenen Zeit abgeschlossen ist, wird es Zeitlimit überschritten werden. Standardmäßig wird der Ausnahmehandler <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> wiederholt die zeitgesteuerte out Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="9af77-130">If the operation is not completed in the specified time, it will be timed out. By default, exception handler of <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> retries the timed out exception.</span></span> <span data-ttu-id="9af77-131">Es wird nicht ändern Timeout für den Vorgang aus den Standardwert empfohlen.</span><span class="sxs-lookup"><span data-stu-id="9af77-131">It is recommended to not change the operation timeout from it's default value.</span></span> 
                </summary>
        <value>
                <span data-ttu-id="9af77-132">Timeout für den Vorgang in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="9af77-132">The operation timeout in seconds.</span></span> <span data-ttu-id="9af77-133">Wenn nicht angegebenen oder kleiner als 0 (null), Standardvorgang Timeout der maximale Wert wird verwendet.</span><span class="sxs-lookup"><span data-stu-id="9af77-133">If not specified or less than zero, default operation timeout of maximum value is used.</span></span> 
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>