<Type Name="WcfServiceRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public sealed class WcfServiceRemotingProviderAttribute : Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WcfServiceRemotingProviderAttribute extends Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WcfServiceRemotingProviderAttribute&#xA;Inherits ServiceRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type WcfServiceRemotingProviderAttribute = class&#xA;    inherit ServiceRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
                <span data-ttu-id="21e65-101">Legt die WCF als Standard-Remoting Transport Dienstanbieter in der Assembly fest.</span><span class="sxs-lookup"><span data-stu-id="21e65-101">Sets WCF as the default service remoting transport provider in the assembly.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="21e65-102">Erstellt eine <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute" /> die festzulegende WCF-Transport als Standard-Remoting Transport Dienstanbieter in der Assembly verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="21e65-102">Constructs a <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute" /> which can be used to set WCF transport as the default service remoting transport provider in the assembly.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseTimeoutInMilliSeconds">
      <MemberSignature Language="C#" Value="public long CloseTimeoutInMilliSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CloseTimeoutInMilliSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CloseTimeoutInMilliSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property CloseTimeoutInMilliSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.CloseTimeoutInMilliSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CloseTimeoutInMilliSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="21e65-103">Ruft ab oder legt den Timeout in Millisekunden vor dem Schließen der Verbindung mit vorhandenen Nachrichten abzuleiten.</span><span class="sxs-lookup"><span data-stu-id="21e65-103">Gets or Sets the timeout in milliseconds to wait before closing the connection to let existing messages drain.</span></span>
            </summary>
        <value>
                <span data-ttu-id="21e65-104">Das Timeout in Millisekunden, die vor dem Schließen der Verbindung um eine vorhandene Ausgleichsmodus Nachrichten warten.</span><span class="sxs-lookup"><span data-stu-id="21e65-104">The timeout in milliseconds to wait before closing the connection to let existing messages drain.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="wcfServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
                <span data-ttu-id="21e65-105">Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="21e65-105">Client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="21e65-106">Erstellt eine Factory V1 Dienst Remoting-Client, der verwendet werden kann die <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> um einen Proxy für die Remoteschnittstelle des Diensts zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="21e65-106">Creates a V1 service remoting client factory that can be used by the <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> to create a proxy for the remoted interface of the service.</span></span>
                </summary>
        <returns>
                <span data-ttu-id="21e65-107">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory" />.</span><span class="sxs-lookup"><span data-stu-id="21e65-107">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="wcfServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
                <span data-ttu-id="21e65-108">Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="21e65-108">Client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="21e65-109">Erstellt eine Dienst-Remoting-Client-Factory, die verwendet werden kann die <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> um einen Proxy für die Remoteschnittstelle des Diensts zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="21e65-109">Creates a service remoting client factory that can be used by the <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> to create a proxy for the remoted interface of the service.</span></span>
                </summary>
        <returns>
                <span data-ttu-id="21e65-110">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory" />.</span><span class="sxs-lookup"><span data-stu-id="21e65-110">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CreateServiceRemotingListener(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="wcfServiceRemotingProviderAttribute.CreateServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
                <span data-ttu-id="21e65-111">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="21e65-111">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="serviceImplementation">
                <span data-ttu-id="21e65-112">Das Dienstobjekt für die Implementierung.</span><span class="sxs-lookup"><span data-stu-id="21e65-112">The service implementation object.</span></span>
            </param>
        <summary>
                <span data-ttu-id="21e65-113">Erstellt einen V1 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="21e65-113">Creates a V1 service remoting listener for remoting the service interface.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="21e65-114">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" /> für den angegebenen Dienst.</span><span class="sxs-lookup"><span data-stu-id="21e65-114">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" /> for the specified service.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="wcfServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2 (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
                <span data-ttu-id="21e65-115">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="21e65-115">The context of the service for which the remoting listener is being constructed.</span></span>
            </param>
        <param name="serviceImplementation">
                <span data-ttu-id="21e65-116">Das Dienstobjekt für die Implementierung.</span><span class="sxs-lookup"><span data-stu-id="21e65-116">The service implementation object.</span></span>
            </param>
        <summary>
                <span data-ttu-id="21e65-117">Erstellt einen V2 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="21e65-117">Creates a V2 service remoting listener for remoting the service interface.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="21e65-118">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" /> für den angegebenen Dienst.</span><span class="sxs-lookup"><span data-stu-id="21e65-118">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" /> for the specified service.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="21e65-119">Ruft ab oder legt die maximale Nachrichtengröße, die über Remoting übertragen werden kann.</span><span class="sxs-lookup"><span data-stu-id="21e65-119">Gets or Sets the maximum message size that can be transferred over remoting.</span></span>
            </summary>
        <value>
                <span data-ttu-id="21e65-120">Die maximale Nachrichtengröße, die über Remoting übertragen werden kann.</span><span class="sxs-lookup"><span data-stu-id="21e65-120">The maximum message size that can be transferred over remoting.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenTimeoutInMilliSeconds">
      <MemberSignature Language="C#" Value="public long OpenTimeoutInMilliSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OpenTimeoutInMilliSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.OpenTimeoutInMilliSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OpenTimeoutInMilliSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OpenTimeoutInMilliSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.OpenTimeoutInMilliSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="21e65-121">Ruft ab oder legt den Timeout in Millisekunden für das Öffnen der Verbindung von Clientseite und wartet auf den Listener, auf der Dienstseite zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="21e65-121">Gets or Sets the timeout in milliseconds for opening the connection from client side and waiting for the listener to open on the service side.</span></span>
            </summary>
        <value>
                <span data-ttu-id="21e65-122">Das Timeout in Millisekunden für das Öffnen der Verbindung von Clientseite und wartet auf den Listener, auf der Dienstseite zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="21e65-122">The timeout in milliseconds for opening the connection from client side and waiting for the listener to open on the service side.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>