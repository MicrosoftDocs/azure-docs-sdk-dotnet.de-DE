<Type Name="WcfCommunicationListener&lt;TServiceContract&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;TServiceContract&gt;">
  <TypeSignature Language="C#" Value="public class WcfCommunicationListener&lt;TServiceContract&gt; : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfCommunicationListener`1&lt;TServiceContract&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfCommunicationListener(Of TServiceContract)&#xA;Implements ICommunicationListener" />
  <TypeSignature Language="F#" Value="type WcfCommunicationListener&lt;'ServiceContract&gt; = class&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TServiceContract" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TServiceContract"><span data-ttu-id="eb5b4-101">Der Typ des WCF-Dienstvertrags.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-101">Type of the WCF service contract.</span></span></typeparam>
    <summary>
            <span data-ttu-id="eb5b4-102">Windows Communication Foundation-basierten Listener für Service Fabric basierend zustandslose oder zustandsbehaftete Dienst.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-102">A Windows Communication Foundation based listener for Service Fabric based stateless or stateful service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="eb5b4-103">Der Kontext des Diensts für die Kommunikation Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-103">The context of the service for which this communication listener is being constructed.</span></span>
            </param>
        <param name="wcfServiceObject">
                <span data-ttu-id="eb5b4-104">WCF-Dienst den angegebenen WCF-Dienstvertrag implementieren.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-104">WCF service implementing the specified WCF service contract.</span></span>
            </param>
        <summary>
                <span data-ttu-id="eb5b4-105">Ein WCF-Konstrukte basierend Kommunikation Listener, die standardmäßige Bindung und Endpunktadresse standardmäßig verwendet.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-105">Constructs a WCF based communication listener that uses default binding and default endpoint address.</span></span>
            </summary>
        <remarks>
          <para>
                    <span data-ttu-id="eb5b4-106">Der Standardlistener, die Bindung wird mit erstellt <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-106">The default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
                </para>
          <para>
                    <span data-ttu-id="eb5b4-107">Die Standardadresse für den Endpunkt wird erstellt, mit der Endpoint-Ressource, die in das Manifest definiert.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-107">The default endpoint address is created using the endpoint resource defined in the service manifest.</span></span> <span data-ttu-id="eb5b4-108">Der Name der endpunktressource stammt aus der WCF-Diensts Vertrag Typ mithilfe <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-108">The name of the endpoint resource is derived from the WCF service contract type using <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> method.</span></span>
                    <span data-ttu-id="eb5b4-109">Wenn übereinstimmende Endpoint-Ressource nicht in das Manifest gefunden wird, wird eine standardmäßige Ressource Endpunktdefinition mit Port 0 (null) verwendet.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-109">If matching endpoint resource is not found in the service manifest, a default endpoint resource definition with port zero is used.</span></span>
                    </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="eb5b4-110">Der Kontext des Diensts für die Kommunikation Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-110">The context of the service for which this communication listener is being constructed.</span></span>
            </param>
        <param name="wcfServiceObject">
                <span data-ttu-id="eb5b4-111">WCF-Dienst den angegebenen WCF-Dienstvertrag implementieren.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-111">WCF service implementing the specified WCF service contract.</span></span>
            </param>
        <param name="listenerBinding">
                <span data-ttu-id="eb5b4-112">Die Bindung, die für den WCF-Endpunkt verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-112">The binding to use for the WCF endpoint.</span></span> <span data-ttu-id="eb5b4-113">Wenn die ListenerBinding nicht angegeben ist, oder es null ist, ein Standardlistener, der Bindung ist mit erstellt <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-113">If the listenerBinding is not specified or it is null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
                </param>
        <param name="address">
                <span data-ttu-id="eb5b4-114">Die abhöradresse für den WCF-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-114">The listen address for the WCF endpoint.</span></span> <span data-ttu-id="eb5b4-115">Wenn die Adresse nicht angegeben ist, oder es null ist, wird eine Standardadresse durch die Suche nach Endpoint-Ressource aus dem Dienstmanifest erstellt.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-115">If the address is not specified or it is null, a default address is created by looking up the endpoint resource from the service manifest.</span></span> <span data-ttu-id="eb5b4-116">Der Ressourcenname Endpunkt stammt aus der WCF-Diensts Vertrag Typ mithilfe <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-116">The endpoint resource name is derived from the WCF service contract type using <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> method.</span></span>
                <span data-ttu-id="eb5b4-117">Wenn übereinstimmende Endpoint-Ressource nicht in das Manifest gefunden wird, wird eine standardmäßige Ressource Endpunktdefinition mit Port 0 (null) verwendet.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-117">If matching endpoint resource is not found in the service manifest, a default endpoint resource definition with port zero is used.</span></span>
                </param>
        <summary>
                <span data-ttu-id="eb5b4-118">Ein WCF-Konstrukte basierend Kommunikation Listener, den angegebenen Listener, die Bindung und Endpunktadresse, die von der angegebenen Endpunktadresse abgeleitet wird.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-118">Constructs a WCF based communication listener that uses specified listener binding and endpoint address derived from the specified endpoint address.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject, System.ServiceModel.Channels.Binding listenerBinding = null, string endpointResourceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject, class System.ServiceModel.Channels.Binding listenerBinding, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0,System.ServiceModel.Channels.Binding,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract * System.ServiceModel.Channels.Binding * string -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject, listenerBinding, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="eb5b4-119">Der Kontext des Diensts für die Kommunikation Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-119">The context of the service for which this communication listener is being constructed.</span></span>
            </param>
        <param name="wcfServiceObject">
                <span data-ttu-id="eb5b4-120">WCF-Dienst den angegebenen WCF-Dienstvertrag implementieren.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-120">WCF service implementing the specified WCF service contract.</span></span>
            </param>
        <param name="listenerBinding">
                <span data-ttu-id="eb5b4-121">Die Bindung, die für den WCF-Endpunkt verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-121">The binding to use for the WCF endpoint.</span></span> <span data-ttu-id="eb5b4-122">Wenn die ListenerBinding nicht angegeben ist, oder es null ist, ein Standardlistener, der Bindung ist mit erstellt <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-122">If the listenerBinding is not specified or it is null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
                </param>
        <param name="endpointResourceName">
                <span data-ttu-id="eb5b4-123">Der Name der endpunktressource definiert, in das Manifest, das verwendet werden soll, um die Adresse für den Listener zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-123">The name of the endpoint resource defined in the service manifest that should be used to create the address for the listener.</span></span> <span data-ttu-id="eb5b4-124">Wenn die EndpointResourceName nicht angegeben ist, oder es null ist, wird der Name abgeleitet, von der WCF-Diensts Vertrag Typ mithilfe <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-124">If the endpointResourceName is not specified or it is null, its name is derived from the WCF service contract type using <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> method.</span></span>
                <span data-ttu-id="eb5b4-125">Wenn übereinstimmende Endpoint-Ressource nicht in das Manifest gefunden wird, wird eine standardmäßige Ressource Endpunktdefinition mit Port 0 (null) verwendet.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-125">If matching endpoint resource is not found in the service manifest, a default endpoint resource definition with port zero is used.</span></span>
                </param>
        <summary>
                <span data-ttu-id="eb5b4-126">Ein WCF-Konstrukte basierend Kommunikation Listener, den angegebenen Listener, die Bindung und Endpunktadresse abgeleitet aus dem angegebenen Endpunktnamen Ressource verwendet.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-126">Constructs a WCF based communication listener that uses specified listener binding and endpoint address derived from the specified endpoint resource name.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="eb5b4-127">Diese Methode bewirkt, dass den Listener Kommunikation zu schließen.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-127">This method causes the communication listener to close.</span></span> <span data-ttu-id="eb5b4-128">Schließen ist ein Endstatus und diese Methode bewirkt, dass des Übergangs nicht ordnungsgemäß geschlossen.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-128">Close is a terminal state and this method causes the transition to close ungracefully.</span></span> <span data-ttu-id="eb5b4-129">Alle ausstehenden Vorgänge (einschließlich schließen) sollte abgebrochen werden, wenn diese Methode aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-129">Any outstanding operations (including close) should be canceled when this method is called.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1/&lt;Microsoft-ServiceFabric-Services-Communication-Runtime-ICommunicationListener-CloseAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="eb5b4-130">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="eb5b4-130">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="eb5b4-131">Diese Methode bewirkt, dass den Listener Kommunikation zu schließen.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-131">This method causes the communication listener to close.</span></span> <span data-ttu-id="eb5b4-132">Schließen ist ein Endstatus und diese Methode ermöglicht die Kommunikation-Listener für den Übergang in diesen Zustand auf ordnungsgemäße Weise.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-132">Close is a terminal state and this method allows the communication listener to transition to this state in a graceful manner.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb5b4-133">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-133">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="eb5b4-134">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="eb5b4-134">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="eb5b4-135">Diese Methode bewirkt, dass die Kommunikation Listener geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-135">This method causes the communication listener to be opened.</span></span> <span data-ttu-id="eb5b4-136">Nach Abschluss der öffnen, der Listener für die Kommunikation wird verwendbar - akzeptiert, und sendet Nachrichten ab.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-136">Once the Open completes, the communication listener becomes usable - accepts and sends messages.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb5b4-137">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-137">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="eb5b4-138">Das Ergebnis der Aufgabe ist die Endpunktzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-138">The result of the Task is the endpoint string.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHost">
      <MemberSignature Language="C#" Value="public System.ServiceModel.ServiceHost ServiceHost { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.ServiceHost ServiceHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.ServiceHost" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHost As ServiceHost" />
      <MemberSignature Language="F#" Value="member this.ServiceHost : System.ServiceModel.ServiceHost" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;.ServiceHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.ServiceHost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="eb5b4-139">Ruft die <see cref="T:System.ServiceModel.ServiceHost" /> , die zum Hosten von WCF-Dienst-Implementierung von diesem Listener verwendet.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-139">Gets the <see cref="T:System.ServiceModel.ServiceHost" /> used by this listener to host the WCF service implementation.</span></span>
                </summary>
        <value>
                <span data-ttu-id="eb5b4-140">Ein <see cref="T:System.ServiceModel.ServiceHost" /> , die zum Hosten von WCF-Dienst-Implementierung von diesem Listener verwendet.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-140">A <see cref="T:System.ServiceModel.ServiceHost" /> used by this listener to host the WCF service implementation.</span></span>
                </value>
        <remarks>
                <span data-ttu-id="eb5b4-141">Der Diensthost wird vom Listener in seinem Konstruktor erstellt.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-141">The service host is created by the listener in its constructor.</span></span> <span data-ttu-id="eb5b4-142">Bevor Sie diese Kommunikation Listener geöffnet wird, von der Laufzeit über <see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" /> -Methode, der Diensthost durch den Zugriff auf ihn über diese Eigenschaft angepasst werden.</span><span class="sxs-lookup"><span data-stu-id="eb5b4-142">Before this communication listener is opened by the runtime via <see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" /> method, the service host can be customized by accessing it via this property.</span></span>
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>