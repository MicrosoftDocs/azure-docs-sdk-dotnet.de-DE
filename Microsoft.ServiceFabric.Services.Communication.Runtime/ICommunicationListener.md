<Type Name="ICommunicationListener" FullName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener">
  <TypeSignature Language="C#" Value="public interface ICommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICommunicationListener" />
  <TypeSignature Language="F#" Value="type ICommunicationListener = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
                <span data-ttu-id="5ae07-101">Definiert die Basisschnittstelle und den Status Computer Vertrag für die Kommunikation Listener für einen Service Fabric-Dienst.</span><span class="sxs-lookup"><span data-stu-id="5ae07-101">Defines the base interface and the state machine contract for the communication listener for a Service Fabric Service.</span></span>
                </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iCommunicationListener.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5ae07-102">Diese Methode bewirkt, dass den Listener Kommunikation zu schließen.</span><span class="sxs-lookup"><span data-stu-id="5ae07-102">This method causes the communication listener to close.</span></span> <span data-ttu-id="5ae07-103">Schließen ist ein Endstatus und diese Methode bewirkt, dass des Übergangs nicht ordnungsgemäß geschlossen.</span><span class="sxs-lookup"><span data-stu-id="5ae07-103">Close is a terminal state and this method causes the transition to close ungracefully.</span></span> <span data-ttu-id="5ae07-104">Alle ausstehenden Vorgänge (einschließlich schließen) sollte abgebrochen werden, wenn diese Methode aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="5ae07-104">Any outstanding operations (including close) should be canceled when this method is called.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCommunicationListener.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5ae07-105">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="5ae07-105">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="5ae07-106">Diese Methode bewirkt, dass den Listener Kommunikation zu schließen.</span><span class="sxs-lookup"><span data-stu-id="5ae07-106">This method causes the communication listener to close.</span></span> <span data-ttu-id="5ae07-107">Schließen ist ein Endstatus und diese Methode ermöglicht die Kommunikation-Listener für den Übergang in diesen Zustand auf ordnungsgemäße Weise.</span><span class="sxs-lookup"><span data-stu-id="5ae07-107">Close is a terminal state and this method allows the communication listener to transition to this state in a graceful manner.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ae07-108">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5ae07-108">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iCommunicationListener.OpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
                <span data-ttu-id="5ae07-109">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="5ae07-109">Cancellation token</span></span>
            </param>
        <summary>
                <span data-ttu-id="5ae07-110">Diese Methode bewirkt, dass die Kommunikation Listener geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="5ae07-110">This method causes the communication listener to be opened.</span></span> <span data-ttu-id="5ae07-111">Nach Abschluss der öffnen, der Listener für die Kommunikation wird verwendbar - akzeptiert, und sendet Nachrichten ab.</span><span class="sxs-lookup"><span data-stu-id="5ae07-111">Once the Open completes, the communication listener becomes usable - accepts and sends messages.</span></span>
                </summary>
        <returns>
            <span data-ttu-id="5ae07-112">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5ae07-112">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="5ae07-113">Das Ergebnis der Aufgabe ist die Endpunktzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5ae07-113">The result of the Task is the endpoint string.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>