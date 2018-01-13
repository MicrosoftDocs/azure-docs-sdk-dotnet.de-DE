<Type Name="NodeFile" FullName="Microsoft.Azure.Batch.NodeFile">
  <TypeSignature Language="C#" Value="public abstract class NodeFile : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NodeFile extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.NodeFile" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NodeFile&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type NodeFile = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a6a4a-101">Macht Methoden und Eigenschaften aus Knoten oder Vorgänge auf Dateien zugreifen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-101">Exposes methods and properties to access files from Nodes or Tasks.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyToStream">
      <MemberSignature Language="C#" Value="public virtual void CopyToStream (System.IO.Stream stream, Microsoft.Azure.Batch.GetFileRequestByteRange byteRange = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyToStream(class System.IO.Stream stream, class Microsoft.Azure.Batch.GetFileRequestByteRange byteRange, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.CopyToStream(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member CopyToStream : System.IO.Stream * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.CopyToStream : System.IO.Stream * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="nodeFile.CopyToStream (stream, byteRange, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="byteRange" Type="Microsoft.Azure.Batch.GetFileRequestByteRange" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="a6a4a-102">Der Stream, in das der Inhalt der Datei kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-102">The stream into which the contents of the file are copied.</span></span></param>
        <param name="byteRange"><span data-ttu-id="a6a4a-103">Die Datei Bytebereich abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-103">The file byte range to retrieve.</span></span> <span data-ttu-id="a6a4a-104">Wenn der Wert null ist, wird die gesamte Datei abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-104">If null, the entire file is retrieved.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6a4a-105">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-105">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="a6a4a-106">Blockierenden Aufruf, um den Inhalt der Datei in dem angegebenen Stream zu kopieren.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-106">Blocking call to copy the contents of the file into the given Stream.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyToStreamAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CopyToStreamAsync (System.IO.Stream stream, Microsoft.Azure.Batch.GetFileRequestByteRange byteRange = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CopyToStreamAsync(class System.IO.Stream stream, class Microsoft.Azure.Batch.GetFileRequestByteRange byteRange, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.CopyToStreamAsync(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CopyToStreamAsync : System.IO.Stream * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="nodeFile.CopyToStreamAsync (stream, byteRange, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="byteRange" Type="Microsoft.Azure.Batch.GetFileRequestByteRange" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="a6a4a-107">Der Stream, in das der Inhalt der Datei kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-107">The stream into which the contents of the file are copied.</span></span></param>
        <param name="byteRange"><span data-ttu-id="a6a4a-108">Die Datei Bytebereich abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-108">The file byte range to retrieve.</span></span> <span data-ttu-id="a6a4a-109">Wenn der Wert null ist, wird die gesamte Datei abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-109">If null, the entire file is retrieved.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6a4a-110">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-110">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="a6a4a-111">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-111">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="a6a4a-112">Startet einen asynchronen Aufruf, um den Inhalt der Datei in dem angegebenen Stream zu kopieren.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-112">Begins an asynchronous call to copy the contents of the file into the given Stream.</span></span>
            </summary>
        <returns><span data-ttu-id="a6a4a-113">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-113">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6a4a-114">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.NodeFile" />.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-114">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.NodeFile" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="a6a4a-115">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-115">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="a6a4a-116">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-116">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="a6a4a-117">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-117">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.Delete(System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Delete (Optional recursive As Nullable(Of Boolean) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Delete : Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="nodeFile.Delete (recursive, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="recursive">
            <span data-ttu-id="a6a4a-118">Wenn die Datei-Path-Parameter ein Verzeichnis anstelle einer Datei darstellt, können Sie den Parameter optional, rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-118">If the file-path parameter represents a directory instead of a file, you can set the optional recursive parameter to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="a6a4a-119">Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-119">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="a6a4a-120">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-120">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="a6a4a-121">Blockierenden Aufruf zum Löschen der Datei an.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-121">Blocking call to delete the file.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteAsync (Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.DeleteAsync(System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="nodeFile.DeleteAsync (recursive, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="recursive">
            <span data-ttu-id="a6a4a-122">Wenn die Datei-Path-Parameter ein Verzeichnis anstelle einer Datei darstellt, können Sie den Parameter optional, rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-122">If the file-path parameter represents a directory instead of a file, you can set the optional recursive parameter to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="a6a4a-123">Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-123">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="a6a4a-124">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-124">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="a6a4a-125">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-125">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="a6a4a-126">Startet einen asynchronen Aufruf zum Löschen der Datei an.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-126">Begins an asynchronous call to delete the file.</span></span>
            </summary>
        <returns><span data-ttu-id="a6a4a-127">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-127">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDirectory">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.IsDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDirectory As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDirectory : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Batch.NodeFile.IsDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6a4a-128">Ruft den Wert, der angibt, ob die Datei ein Verzeichnis ist.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-128">Gets the value that indicates whether the file is a directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Batch.NodeFile.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Obsolete as of 02/2017. Use Path instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6a4a-129">Ruft den Namen der Datei ab.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-129">Gets the name of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.Batch.NodeFile.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6a4a-130">Ruft den Pfad der Datei ab.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-130">Gets the path of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.FileProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.FileProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As FileProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Batch.FileProperties" Usage="Microsoft.Azure.Batch.NodeFile.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.FileProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6a4a-131">Ruft die FileProperties der Datei ab.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-131">Gets the FileProperties of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsString">
      <MemberSignature Language="C#" Value="public string ReadAsString (System.Text.Encoding encoding = null, Microsoft.Azure.Batch.GetFileRequestByteRange byteRange = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ReadAsString(class System.Text.Encoding encoding, class Microsoft.Azure.Batch.GetFileRequestByteRange byteRange, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.ReadAsString(System.Text.Encoding,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ReadAsString : System.Text.Encoding * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; string" Usage="nodeFile.ReadAsString (encoding, byteRange, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="byteRange" Type="Microsoft.Azure.Batch.GetFileRequestByteRange" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="encoding"><span data-ttu-id="a6a4a-132">Die Codierung verwendet, zum Interpretieren der Dateidaten.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-132">The encoding used to interpret the file data.</span></span> <span data-ttu-id="a6a4a-133">Wenn kein Wert oder Null angegeben wird, wird die UTF8 verwendet.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-133">If no value or null is specified, UTF8 is used.</span></span></param>
        <param name="byteRange"><span data-ttu-id="a6a4a-134">Die Datei Bytebereich abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-134">The file byte range to retrieve.</span></span> <span data-ttu-id="a6a4a-135">Wenn der Wert null ist, wird die gesamte Datei abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-135">If null, the entire file is retrieved.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6a4a-136">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-136">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="a6a4a-137">Blockierenden Aufruf, um den Inhalt der Datei als Zeichenfolge zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-137">Blocking call to return the contents of the file as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="a6a4a-138">Eine Zeichenfolge mit dem Inhalt der Datei.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-138">A string containing the contents of the file.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsStringAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; ReadAsStringAsync (System.Text.Encoding encoding = null, Microsoft.Azure.Batch.GetFileRequestByteRange byteRange = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; ReadAsStringAsync(class System.Text.Encoding encoding, class Microsoft.Azure.Batch.GetFileRequestByteRange byteRange, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.ReadAsStringAsync(System.Text.Encoding,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReadAsStringAsync : System.Text.Encoding * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="nodeFile.ReadAsStringAsync (encoding, byteRange, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.NodeFile/&lt;ReadAsStringAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="byteRange" Type="Microsoft.Azure.Batch.GetFileRequestByteRange" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encoding"><span data-ttu-id="a6a4a-139">Die Codierung verwendet, zum Interpretieren der Dateidaten.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-139">The encoding used to interpret the file data.</span></span> <span data-ttu-id="a6a4a-140">Wenn kein Wert oder Null angegeben wird, wird die UTF8 verwendet.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-140">If no value or null is specified, UTF8 is used.</span></span></param>
        <param name="byteRange"><span data-ttu-id="a6a4a-141">Die Datei Bytebereich abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-141">The file byte range to retrieve.</span></span> <span data-ttu-id="a6a4a-142">Wenn der Wert null ist, wird die gesamte Datei abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-142">If null, the entire file is retrieved.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6a4a-143">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-143">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="a6a4a-144">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-144">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="a6a4a-145">Startet die asynchronen Aufruf, um den Inhalt der Datei als Zeichenfolge zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-145">Begins asynchronous call to return the contents of the file as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="a6a4a-146">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-146">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public abstract void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="nodeFile.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="a6a4a-147">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-147">The detail level for the refresh.</span></span>  <span data-ttu-id="a6a4a-148">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.NodeFile.Name" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-148">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.NodeFile.Name" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6a4a-149">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-149">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="a6a4a-150">Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.NodeFile" />.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-150">Refreshes the current <see cref="T:Microsoft.Azure.Batch.NodeFile" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="nodeFile.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="a6a4a-151">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-151">The detail level for the refresh.</span></span>  <span data-ttu-id="a6a4a-152">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.NodeFile.Name" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-152">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.NodeFile.Name" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6a4a-153">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-153">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="a6a4a-154">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-154">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="a6a4a-155">Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.NodeFile" />.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-155">Refreshes the current <see cref="T:Microsoft.Azure.Batch.NodeFile" />.</span></span>
            </summary>
        <returns><span data-ttu-id="a6a4a-156">Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Aktualisierungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-156">A <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous refresh operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.NodeFile.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6a4a-157">Ruft die URL der Datei ab.</span><span class="sxs-lookup"><span data-stu-id="a6a4a-157">Gets the URL of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>