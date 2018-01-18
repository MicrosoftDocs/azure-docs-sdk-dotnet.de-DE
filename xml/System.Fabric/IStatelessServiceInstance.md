<Type Name="IStatelessServiceInstance" FullName="System.Fabric.IStatelessServiceInstance">
  <TypeSignature Language="C#" Value="public interface IStatelessServiceInstance" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServiceInstance" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServiceInstance" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServiceInstance" />
  <TypeSignature Language="F#" Value="type IStatelessServiceInstance = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="4314d-101">Definiert das Verhalten, die den Lebenszyklus einer statusfreien Dienstinstanz, z. B. starten, Initialisierung und Herunterfahren bestimmt.</span><span class="sxs-lookup"><span data-stu-id="4314d-101">Defines behavior that governs the lifecycle of a stateless service instance, such as startup, initialization, and shutdown.</span></span> </para>
      <remarks>
            <span data-ttu-id="4314d-102">Zustandslose Diensttypen müssen diese Schnittstelle implementieren.</span><span class="sxs-lookup"><span data-stu-id="4314d-102">Stateless service types must implement this interface.</span></span> <span data-ttu-id="4314d-103">Die <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statelessservice">zuverlässige zustandslosen Diensts</see> implementiert diese Schnittstelle und Instanz Lifecycle intern behandelt.</span><span class="sxs-lookup"><span data-stu-id="4314d-103">The <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statelessservice">Reliable Stateless service</see> implements this interface and handles instance lifecycle internally.</span></span>
            </remarks>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iStatelessServiceInstance.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para> <span data-ttu-id="4314d-104">Wird dieser Instanz durch Aufruf der synchronen Methode nicht ordnungsgemäß beendet.</span><span class="sxs-lookup"><span data-stu-id="4314d-104">Terminates this instance ungracefully with this synchronous method call.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="4314d-105">Beispiele für geordnete und ungeordnete Abbrüche Beendigung sind Netzwerkprobleme, wodurch Service Fabric-Prozess heruntergefahren und die Verwendung von <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> Bericht eine <see cref="F:System.Fabric.FaultType.Permanent" /> Fehler.</span><span class="sxs-lookup"><span data-stu-id="4314d-105">Examples of ungraceful termination are network issues resulting in Service Fabric process shutdown and the use of <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> to report a <see cref="F:System.Fabric.FaultType.Permanent" /> fault.</span></span> <span data-ttu-id="4314d-106">Wenn die Dienstinstanz diese Methode empfängt, sollten sie sofort freigeben und bereinigen Sie alle Verweise und zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="4314d-106">When the service instance receives this method, it should immediately release and clean up all references and return.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStatelessServiceInstance.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="4314d-107">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4314d-107">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="4314d-108">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4314d-108">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4314d-109">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="4314d-109">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4314d-110">Schließt dieser Dienstinstanz ordnungsgemäß, wenn die Dienstinstanz heruntergefahren wird.</span><span class="sxs-lookup"><span data-stu-id="4314d-110">Closes this service instance gracefully when the service instance is being shut down.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4314d-111">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="4314d-111">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatelessServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatelessServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.Initialize(System.Fabric.StatelessServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatelessServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatelessServiceInitializationParameters -&gt; unit" Usage="iStatelessServiceInstance.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatelessServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para><span data-ttu-id="4314d-112"><see cref="T:System.Fabric.StatelessServiceInitializationParameters" /> für diesen Dienst.</span><span class="sxs-lookup"><span data-stu-id="4314d-112">The <see cref="T:System.Fabric.StatelessServiceInitializationParameters" /> for this service.</span></span></para>
        </param>
        <summary>
          <para> <span data-ttu-id="4314d-113">Initialisiert eine neue Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="4314d-113">Initializes a newly created service instance.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Fabric.IStatelessServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(class System.Fabric.IStatelessServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.OpenAsync(System.Fabric.IStatelessServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.IStatelessServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iStatelessServiceInstance.OpenAsync (partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Approved public API.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partition" Type="System.Fabric.IStatelessServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partition">
          <para>
                <span data-ttu-id="4314d-114">Die <see cref="T:System.Fabric.IStatelessServicePartition" /> , die dieser Instanz zugeordnet ist</span><span class="sxs-lookup"><span data-stu-id="4314d-114">The <see cref="T:System.Fabric.IStatelessServicePartition" /> that this instance is associated with</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4314d-115">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4314d-115">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="4314d-116">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4314d-116">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4314d-117">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="4314d-117">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4314d-118">Wird eine initialisierten-Dienstinstanz geöffnet, sodass es von Clients kontaktiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="4314d-118">Opens an initialized service instance so that it can be contacted by clients.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4314d-119">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ <see cref="T:System.String" />.</span><span class="sxs-lookup"><span data-stu-id="4314d-119">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="4314d-120">Öffnen eine Instanz zustandslosen Diensts gibt an, dass der Dienst jetzt aufgelöst werden kann und durch den Dienst für Clients sichtbar ist.</span><span class="sxs-lookup"><span data-stu-id="4314d-120">Opening an instance stateless service indicates that the service is now resolvable and discoverable by service clients.</span></span> <span data-ttu-id="4314d-121">Die Zeichenfolge, die zurückgegeben wird, ist die Adresse dieser Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="4314d-121">The string that is returned is the address of this service instance.</span></span> <span data-ttu-id="4314d-122">Die Adresse der Dienstname über naming Service Fabric zugeordnet und für Clients, die den Dienst über beheben zurückgegeben <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />.</span><span class="sxs-lookup"><span data-stu-id="4314d-122">The address is associated with the service name via Service Fabric naming and returned to clients that resolve the service via <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>