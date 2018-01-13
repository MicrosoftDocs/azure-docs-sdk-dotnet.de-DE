<Type Name="IConfigurationRetriever&lt;T&gt;" FullName="Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IConfigurationRetriever&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConfigurationRetriever`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConfigurationRetriever(Of T)" />
  <TypeSignature Language="F#" Value="type IConfigurationRetriever&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="b2798-101">Der Typ der Konfigurationsmetadaten.</span><span class="sxs-lookup"><span data-stu-id="b2798-101">The type of the configuration metadata.</span></span></typeparam>
    <summary>
            <span data-ttu-id="b2798-102">Schnittstelle, die Methoden zum Abrufen von Konfiguration definiert.</span><span class="sxs-lookup"><span data-stu-id="b2798-102">Interface that defines methods to retrieve configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetConfigurationAsync (string address, Microsoft.IdentityModel.Protocols.IDocumentRetriever retriever, System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetConfigurationAsync(string address, class Microsoft.IdentityModel.Protocols.IDocumentRetriever retriever, valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1.GetConfigurationAsync(System.String,Microsoft.IdentityModel.Protocols.IDocumentRetriever,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationAsync (address As String, retriever As IDocumentRetriever, cancel As CancellationToken) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationAsync : string * Microsoft.IdentityModel.Protocols.IDocumentRetriever * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iConfigurationRetriever.GetConfigurationAsync (address, retriever, cancel)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="retriever" Type="Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="b2798-103">Die Adresse des Discovery-Dokuments.</span><span class="sxs-lookup"><span data-stu-id="b2798-103">Address of the discovery document.</span></span></param>
        <param name="retriever"><span data-ttu-id="b2798-104">Die <see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" /> zu verwenden, um den Discoverydokument zu lesen.</span><span class="sxs-lookup"><span data-stu-id="b2798-104">The <see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" /> to use to read the discovery document.</span></span></param>
        <param name="cancel"><span data-ttu-id="b2798-105">Ein Abbruchtoken, das von anderen Objekten oder Threads verwendet werden kann, um Nachricht vom Abbruch zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="b2798-105">A cancellation token that can be used by other objects or threads to receive notice of cancellation.</span></span> <span data-ttu-id="b2798-106"><see cref="T:System.Threading.CancellationToken" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="b2798-106"><see cref="T:System.Threading.CancellationToken" />.</span></span></param>
        <summary>
            <span data-ttu-id="b2798-107">Ruft eine ausgefüllte Konfiguration erhält eine Adresse und ein <see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" />.</span><span class="sxs-lookup"><span data-stu-id="b2798-107">Retrieves a populated configuration given an address and an <see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" />.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>