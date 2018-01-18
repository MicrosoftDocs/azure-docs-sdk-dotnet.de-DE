<Type Name="FileDocumentRetriever" FullName="Microsoft.IdentityModel.Protocols.FileDocumentRetriever">
  <TypeSignature Language="C#" Value="public class FileDocumentRetriever : Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileDocumentRetriever extends System.Object implements class Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.FileDocumentRetriever" />
  <TypeSignature Language="VB.NET" Value="Public Class FileDocumentRetriever&#xA;Implements IDocumentRetriever" />
  <TypeSignature Language="F#" Value="type FileDocumentRetriever = class&#xA;    interface IDocumentRetriever" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Protocols.IDocumentRetriever</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="67765-101">Eine lokale Datei vom Datenträger gelesen.</span><span class="sxs-lookup"><span data-stu-id="67765-101">Reads a local file from the disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileDocumentRetriever ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.FileDocumentRetriever.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="67765-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.IdentityModel.Protocols.FileDocumentRetriever" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="67765-102">Initializes a new instance of the <see cref="T:Microsoft.IdentityModel.Protocols.FileDocumentRetriever" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetDocumentAsync (string address, System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GetDocumentAsync(string address, valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.FileDocumentRetriever.GetDocumentAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDocumentAsync (address As String, cancel As CancellationToken) As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetDocumentAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.GetDocumentAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="fileDocumentRetriever.GetDocumentAsync (address, cancel)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Protocols.IDocumentRetriever.GetDocumentAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.DebuggerStepThrough</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Protocols.FileDocumentRetriever/&lt;GetDocumentAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="67765-103">Den vollqualifizierten Pfad zu einer Datei.</span><span class="sxs-lookup"><span data-stu-id="67765-103">Fully qualified path to a file.</span></span></param>
        <param name="cancel">
          <span data-ttu-id="67765-104"><see cref="T:System.Threading.CancellationToken" />nicht verwendet.</span><span class="sxs-lookup"><span data-stu-id="67765-104"><see cref="T:System.Threading.CancellationToken" /> not used.</span></span></param>
        <summary>
            <span data-ttu-id="67765-105">Liest ein Dokument mit <see cref="T:System.IO.FileStream" />.</span><span class="sxs-lookup"><span data-stu-id="67765-105">Reads a document using <see cref="T:System.IO.FileStream" />.</span></span>
            </summary>
        <returns><span data-ttu-id="67765-106">UTF8 Decodierung von Bytes in der Datei.</span><span class="sxs-lookup"><span data-stu-id="67765-106">UTF8 decoding of bytes in the file.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="67765-107">Wenn die Adresse Null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="67765-107">If address is null or whitespace.</span></span></exception>
        <exception cref="T:System.IO.IOException"><span data-ttu-id="67765-108">mit der inneren Ausnahme, die die ursprüngliche Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="67765-108">with inner expection containing the original exception.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>