<Type Name="FabricClient+InfrastructureServiceClient" FullName="System.Fabric.FabricClient+InfrastructureServiceClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/InfrastructureServiceClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="F#" Value="type FabricClient.InfrastructureServiceClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="5461c-101">Stellt Methoden zum Ausführen von Vorgängen Infrastruktur bereit.</span><span class="sxs-lookup"><span data-stu-id="5461c-101">Provides methods for performing infrastructure-specific operations.</span></span></para>
      <para><span data-ttu-id="5461c-102">Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5461c-102">This class supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="5461c-103">Die InfrastructureService muss aktiviert sein, bevor dieser Client verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5461c-103">The InfrastructureService must be enabled before this client can be used.</span></span> <span data-ttu-id="5461c-104">Die InfrastructureService wird nur auf einige Infrastrukturen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="5461c-104">The InfrastructureService is only supported on some infrastructures.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="InvokeInfrastructureCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureCommandAsync (Uri serviceName, string command);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureCommandAsync(class System.Uri serviceName, string command) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureCommandAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeInfrastructureCommandAsync (serviceName As Uri, command As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureCommandAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureCommandAsync (serviceName, command)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="5461c-105">Der Name der Ziel-Infrastruktur-Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="5461c-105">The name of the target infrastructure service instance.</span></span></para>
        </param>
        <param name="command">
          <para><span data-ttu-id="5461c-106">Der Text des Befehls, der aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5461c-106">The text of the command to be invoked.</span></span>  <span data-ttu-id="5461c-107">Der Inhalt des Befehls ist Infrastruktur spezifisch.</span><span class="sxs-lookup"><span data-stu-id="5461c-107">The content of the command is infrastructure-specific.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5461c-108">Ruft asynchron einen administrativen-Befehl auf der Dienstinstanz des angegebenen Infrastruktur auf.</span><span class="sxs-lookup"><span data-stu-id="5461c-108">Asynchronously invokes an administrative command on the given infrastructure service instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5461c-109">Die Antwort vom Dienst Infrastruktur.</span><span class="sxs-lookup"><span data-stu-id="5461c-109">The response from the infrastructure service.</span></span> <span data-ttu-id="5461c-110">Das Format der Antwort ist eine JSON-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5461c-110">The response format is a JSON string.</span></span> <span data-ttu-id="5461c-111">Der Inhalt der Antwort wird, hängt davon ab, welcher Befehl ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="5461c-111">The contents of the response depend on which command was issued.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureCommandAsync (Uri serviceName, string command, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureCommandAsync(class System.Uri serviceName, string command, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureCommandAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureCommandAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureCommandAsync (serviceName, command, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="5461c-112">Der Name der Ziel-Infrastruktur-Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="5461c-112">The name of the target infrastructure service instance.</span></span></para>
        </param>
        <param name="command">
          <para><span data-ttu-id="5461c-113">Der Text des Befehls, der aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5461c-113">The text of the command to be invoked.</span></span>  <span data-ttu-id="5461c-114">Der Inhalt des Befehls ist Infrastruktur spezifisch.</span><span class="sxs-lookup"><span data-stu-id="5461c-114">The content of the command is infrastructure-specific.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="5461c-115">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="5461c-115">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="5461c-116">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5461c-116">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="5461c-117">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5461c-117">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="5461c-118">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="5461c-118">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5461c-119">Ruft asynchron einen administrativen-Befehl für einen Dienst Infrastruktur auf.</span><span class="sxs-lookup"><span data-stu-id="5461c-119">Asynchronously invokes an administrative command on an infrastructure service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5461c-120">Die Antwort vom Dienst Infrastruktur.</span><span class="sxs-lookup"><span data-stu-id="5461c-120">The response from the infrastructure service.</span></span> <span data-ttu-id="5461c-121">Das Format der Antwort ist eine JSON-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5461c-121">The response format is a JSON string.</span></span> <span data-ttu-id="5461c-122">Der Inhalt der Antwort wird, hängt davon ab, welcher Befehl ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="5461c-122">The contents of the response depend on which command was issued.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureQueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureQueryAsync (Uri serviceName, string command);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureQueryAsync(class System.Uri serviceName, string command) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureQueryAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeInfrastructureQueryAsync (serviceName As Uri, command As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureQueryAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureQueryAsync (serviceName, command)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="5461c-123">Der Name der Ziel-Infrastruktur-Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="5461c-123">The name of the target infrastructure service instance.</span></span></para>
        </param>
        <param name="command">
          <para><span data-ttu-id="5461c-124">Der Text des Befehls, der aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5461c-124">The text of the command to be invoked.</span></span>  <span data-ttu-id="5461c-125">Der Inhalt des Befehls ist Infrastruktur spezifisch.</span><span class="sxs-lookup"><span data-stu-id="5461c-125">The content of the command is infrastructure-specific.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5461c-126">Ruft asynchron eine nur-Lese Abfrage auf der Dienstinstanz des angegebenen Infrastruktur auf.</span><span class="sxs-lookup"><span data-stu-id="5461c-126">Asynchronously invokes a read-only query on the given infrastructure service instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5461c-127">Die Antwort vom Dienst Infrastruktur.</span><span class="sxs-lookup"><span data-stu-id="5461c-127">The response from the infrastructure service.</span></span> <span data-ttu-id="5461c-128">Das Format der Antwort ist eine JSON-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5461c-128">The response format is a JSON string.</span></span> <span data-ttu-id="5461c-129">Der Inhalt der Antwort wird, hängt davon ab, welcher Befehl ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="5461c-129">The contents of the response depend on which command was issued.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureQueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureQueryAsync (Uri serviceName, string command, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureQueryAsync(class System.Uri serviceName, string command, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureQueryAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureQueryAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureQueryAsync (serviceName, command, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="5461c-130">Der Name der Ziel-Infrastruktur-Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="5461c-130">The name of the target infrastructure service instance.</span></span></para>
        </param>
        <param name="command">
          <para><span data-ttu-id="5461c-131">Der Text des Befehls, der aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5461c-131">The text of the command to be invoked.</span></span>  <span data-ttu-id="5461c-132">Der Inhalt des Befehls ist Infrastruktur spezifisch.</span><span class="sxs-lookup"><span data-stu-id="5461c-132">The content of the command is infrastructure-specific.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="5461c-133">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="5461c-133">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="5461c-134">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5461c-134">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="5461c-135">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5461c-135">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="5461c-136">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="5461c-136">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5461c-137">Ruft asynchron eine nur-Lese Abfrage auf der Dienstinstanz des angegebenen Infrastruktur auf.</span><span class="sxs-lookup"><span data-stu-id="5461c-137">Asynchronously invokes a read-only query on the given infrastructure service instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5461c-138">Die Antwort vom Dienst Infrastruktur.</span><span class="sxs-lookup"><span data-stu-id="5461c-138">The response from the infrastructure service.</span></span> <span data-ttu-id="5461c-139">Das Format der Antwort ist eine JSON-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5461c-139">The response format is a JSON string.</span></span> <span data-ttu-id="5461c-140">Der Inhalt der Antwort wird, hängt davon ab, welcher Befehl ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="5461c-140">The contents of the response depend on which command was issued.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>