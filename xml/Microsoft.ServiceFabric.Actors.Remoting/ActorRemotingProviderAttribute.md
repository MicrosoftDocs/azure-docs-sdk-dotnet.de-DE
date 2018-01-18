<Type Name="ActorRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public abstract class ActorRemotingProviderAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorRemotingProviderAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorRemotingProviderAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type ActorRemotingProviderAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4eda8-101">Dies ist ein Basistyp für das Attribut, das festlegt Remoting Standardanbieter für das Remoting zu verwenden, die Akteur-Schnittstellen definiert, oder in der Assembly verwendet.</span><span class="sxs-lookup"><span data-stu-id="4eda8-101">This is a base type for attribute that sets the default remoting provider to use for remoting the actor interfaces defined or used in the assembly.</span></span>
            </summary>
    <remarks>
      <para>
                <span data-ttu-id="4eda8-102">Auf Dienstseite-Implementierung des Attributs gesucht wird durch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> an Standardeinstellung erstellen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> dafür.</span><span class="sxs-lookup"><span data-stu-id="4eda8-102">On service side, implementation of this attribute is looked up by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> to create default <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for it.</span></span> 
                </para>
      <para>
                <span data-ttu-id="4eda8-103">Auf Clientseite-Implementierung des Attributs gesucht wird durch <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> Konstruktor zum Erstellen eines standardmäßigen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> wenn er nicht angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="4eda8-103">On client side, implementation of this attribute is looked up by <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> constructor to create a default <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> when it is not specified.</span></span>
                </para>
      <para>
                <span data-ttu-id="4eda8-104">Beachten Sie, die auf Client side Wenn Akteur Proxy erstellt wird, mithilfe der statischen <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> -Klasse, verwendet den Standardwert <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> einmal und daher die Anbieter-Suche erfolgt, nur zum ersten Mal in einer Assembly, wonach die gleiche Anbieter verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="4eda8-104">Note that on client side when actor proxy is created using the static <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> class, it uses a default <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> once and hence the provider lookup happens only for the first time in an assembly, after which the same provider is used.</span></span>
                </para>
      <para>
                <span data-ttu-id="4eda8-105">Dieses Attribut ist in der folgenden Reihenfolge gesucht: <list type="number"> <item> im Eintrag <see cref="T:System.Reflection.Assembly" /> durch Aufrufen der Methode abgerufenen <see cref="M:System.Reflection.Assembly.GetEntryAssembly" /> </item> <item> In der <see cref="T:System.Reflection.Assembly" /> , definiert der remote-Schnittstelle für die Listener oder Proxy wird erstellt.</item></list></span><span class="sxs-lookup"><span data-stu-id="4eda8-105">This attribute is looked up in the following order: <list type="number"><item> In the entry <see cref="T:System.Reflection.Assembly" /> obtained by calling method <see cref="M:System.Reflection.Assembly.GetEntryAssembly" /></item><item> In the <see cref="T:System.Reflection.Assembly" /> that defines the remote interface for which listener or proxy is being created. </item></list></span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ActorRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
                <span data-ttu-id="4eda8-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4eda8-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="actorRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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
                <span data-ttu-id="4eda8-107">Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="4eda8-107">Client implementation where the callbacks should be dispatched.</span></span>
            </param>
        <summary>
                <span data-ttu-id="4eda8-108">Erstellt eine Verbindung zu den Schnittstellen prozessübergreifendes Akteur als Remoting-Client eine Dienstzuordnungsinstanz an.</span><span class="sxs-lookup"><span data-stu-id="4eda8-108">Creates a service remoting client factory to connected to the remoted actor interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="4eda8-109">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> , die verwendet werden kann, mit <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> um Akteur Proxy mit dem Akteur über Remote Akteur Schnittstelle sprechen zu generieren.</span><span class="sxs-lookup"><span data-stu-id="4eda8-109">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> that can be used with <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> to generate actor proxy to talk to the actor over remoted actor interface.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="actorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler"><span data-ttu-id="4eda8-110">Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="4eda8-110">Client implementation where the callbacks should be dispatched.</span></span></param>
        <summary>
            <span data-ttu-id="4eda8-111">Erstellt eine Dienst-Remoting-Client-Factory, die verwendet werden kann die <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> um einen Proxy für die Remoteschnittstelle des Diensts zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4eda8-111">Creates a service remoting client factory that can be used by the <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> to create a proxy for the remoted interface of the service.</span></span>
            </summary>
        <returns><span data-ttu-id="4eda8-112"><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />.</span><span class="sxs-lookup"><span data-stu-id="4eda8-112">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingListener(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="actorRemotingProviderAttribute.CreateServiceRemotingListener actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                <span data-ttu-id="4eda8-113">Die Implementierung der Akteur-Dienst, der die Akteure hostet, deren Schnittstellen Remote ausgeführt werden muss.</span><span class="sxs-lookup"><span data-stu-id="4eda8-113">The implementation of the actor service that hosts the actors whose interfaces needs to be remoted.</span></span>
                </param>
        <summary>
                <span data-ttu-id="4eda8-114">Erstellt einen Dienst Remoting-Listener für das Remoting die Akteur-Schnittstellen.</span><span class="sxs-lookup"><span data-stu-id="4eda8-114">Creates a service remoting listener for remoting the actor interfaces.</span></span>
            </summary>
        <returns>
                <span data-ttu-id="4eda8-115">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für den angegebenen Akteur-Dienst.</span><span class="sxs-lookup"><span data-stu-id="4eda8-115">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified actor service.</span></span>
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingListenerV2(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListenerV2 : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="actorRemotingProviderAttribute.CreateServiceRemotingListenerV2 actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                <span data-ttu-id="4eda8-116">Die Implementierung der Akteur-Dienst, der die Akteure hostet, deren Schnittstellen Remote ausgeführt werden muss.</span><span class="sxs-lookup"><span data-stu-id="4eda8-116">The implementation of the actor service that hosts the actors whose interfaces needs to be remoted.</span></span>
                </param>
        <summary>
            <span data-ttu-id="4eda8-117">Erstellt einen V2 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="4eda8-117">Creates a V2 service remoting listener for remoting the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="4eda8-118">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für den angegebenen Dienst.</span><span class="sxs-lookup"><span data-stu-id="4eda8-118">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for the specified service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingClient" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingClient As RemotingClient" />
      <MemberSignature Language="F#" Value="member this.RemotingClient : Microsoft.ServiceFabric.Services.Remoting.RemotingClient with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4eda8-119">RemotingClient wird verwendet, um zu bestimmen, wo V1 oder V2 Remoting Client verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="4eda8-119">RemotingClient is used to determine where  V1 or V2 remoting Client is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingListener">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingListener" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingListener As RemotingListener" />
      <MemberSignature Language="F#" Value="member this.RemotingListener : Microsoft.ServiceFabric.Services.Remoting.RemotingListener with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4eda8-120">RemotingListener wird verwendet, um zu bestimmen, auf dem Listener in V1, V2 oder Komprimierungsmodus ist.</span><span class="sxs-lookup"><span data-stu-id="4eda8-120">RemotingListener is used to determine where listener is in V1, V2 or Compact Mode.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>