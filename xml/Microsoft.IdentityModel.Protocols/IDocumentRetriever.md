<Type Name="IDocumentRetriever" FullName="Microsoft.IdentityModel.Protocols.IDocumentRetriever">
  <TypeSignature Language="C#" Value="public interface IDocumentRetriever" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDocumentRetriever" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDocumentRetriever" />
  <TypeSignature Language="F#" Value="type IDocumentRetriever = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="393c4-101">Schnittstelle, ein Dokument Faktenabrufer definiert, die das Dokument als Zeichenfolge zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="393c4-101">Interface that defines a document retriever that returns the document as a string.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetDocumentAsync (string address, System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GetDocumentAsync(string address, valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.IDocumentRetriever.GetDocumentAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDocumentAsync (address As String, cancel As CancellationToken) As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetDocumentAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iDocumentRetriever.GetDocumentAsync (address, cancel)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="393c4-102">der Speicherort des Dokuments.</span><span class="sxs-lookup"><span data-stu-id="393c4-102">location of document.</span></span></param>
        <param name="cancel">
          <span data-ttu-id="393c4-103"><see cref="T:System.Threading.CancellationToken" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="393c4-103"><see cref="T:System.Threading.CancellationToken" />.</span></span></param>
        <summary>
            <span data-ttu-id="393c4-104">Ruft ein Dokument aus einer Adresse ab.</span><span class="sxs-lookup"><span data-stu-id="393c4-104">Obtains a document from an address.</span></span>
            </summary>
        <returns><span data-ttu-id="393c4-105">Dokument als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="393c4-105">document as a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>