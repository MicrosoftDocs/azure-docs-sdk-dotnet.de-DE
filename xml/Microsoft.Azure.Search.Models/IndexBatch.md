<Type Name="IndexBatch" FullName="Microsoft.Azure.Search.Models.IndexBatch">
  <TypeSignature Language="C#" Value="public class IndexBatch : Microsoft.Azure.Search.Models.IndexBatchBase&lt;Microsoft.Azure.Search.Models.IndexAction,Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexBatch extends Microsoft.Azure.Search.Models.IndexBatchBase`2&lt;class Microsoft.Azure.Search.Models.IndexAction, class Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexBatch" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexBatch&#xA;Inherits IndexBatchBase(Of IndexAction, Document)" />
  <TypeSignature Language="F#" Value="type IndexBatch = class&#xA;    inherit IndexBatchBase&lt;IndexAction, Document&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.IndexBatchBase&lt;Microsoft.Azure.Search.Models.IndexAction,Microsoft.Azure.Search.Models.Document&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TAction">Microsoft.Azure.Search.Models.IndexAction</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TDoc">Microsoft.Azure.Search.Models.Document</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="38869-101">Enthält einen Batch von Dokument hochladen, Zusammenführen und/oder Delete-Vorgänge der Azure Search-Index an.</span><span class="sxs-lookup"><span data-stu-id="38869-101">Contains a batch of document upload, merge, and/or delete operations to send to the Azure Search index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&gt; actions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.IndexAction&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.IndexAction})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (actions As IEnumerable(Of IndexAction))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexBatch : seq&lt;Microsoft.Azure.Search.Models.IndexAction&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="new Microsoft.Azure.Search.Models.IndexBatch actions" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actions" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&gt;" />
      </Parameters>
      <Docs>
        <param name="actions"><span data-ttu-id="38869-102">Die indexaktionen in den Batch aufgenommen werden soll.</span><span class="sxs-lookup"><span data-stu-id="38869-102">The index actions to include in the batch.</span></span></param>
        <summary>
            <span data-ttu-id="38869-103">Initialisiert eine neue Instanz der IndexBatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="38869-103">Initializes a new instance of the IndexBatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.Document&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.Document})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (documents As IEnumerable(Of Document)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member Delete : seq&lt;Microsoft.Azure.Search.Models.Document&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.Delete documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt;" />
      </Parameters>
      <Docs>
        <param name="documents"><span data-ttu-id="38869-104">Die Dokumente zu löschen; Felder als die Schlüssel werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="38869-104">The documents to delete; Fields other than the key are ignored.</span></span></param>
        <summary>
            <span data-ttu-id="38869-105">Erstellt eine neue IndexBatch für das Löschen eines Batches von Dokumenten an.</span><span class="sxs-lookup"><span data-stu-id="38869-105">Creates a new IndexBatch for deleting a batch of documents.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-106">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-106">A new IndexBatch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch Delete (string keyName, System.Collections.Generic.IEnumerable&lt;string&gt; keyValues);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch Delete(string keyName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; keyValues) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Delete(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (keyName As String, keyValues As IEnumerable(Of String)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member Delete : string * seq&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.Delete (keyName, keyValues)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyValues" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="38869-107">Der Name des Schlüsselfelds, die Dokumente im Index eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="38869-107">The name of the key field that uniquely identifies documents in the index.</span></span></param>
        <param name="keyValues"><span data-ttu-id="38869-108">Die Schlüssel der Dokumente zu löschen.</span><span class="sxs-lookup"><span data-stu-id="38869-108">The keys of the documents to delete.</span></span></param>
        <summary>
            <span data-ttu-id="38869-109">Erstellt eine neue IndexBatch für das Löschen eines Batches von Dokumenten an.</span><span class="sxs-lookup"><span data-stu-id="38869-109">Creates a new IndexBatch for deleting a batch of documents.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-110">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-110">A new IndexBatch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; Delete&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;T&gt; documents) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; Delete&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;!!T&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Delete``1(System.Collections.Generic.IEnumerable{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete(Of T As Class) (documents As IEnumerable(Of T)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member Delete : seq&lt;'T (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.Delete documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="38869-111">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="38869-111">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="38869-112">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="38869-112">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="documents"><span data-ttu-id="38869-113">Die Dokumente zu löschen; Felder als die Schlüssel werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="38869-113">The documents to delete; Fields other than the key are ignored.</span></span></param>
        <summary>
            <span data-ttu-id="38869-114">Erstellt eine neue IndexBatch für das Löschen eines Batches von Dokumenten an.</span><span class="sxs-lookup"><span data-stu-id="38869-114">Creates a new IndexBatch for deleting a batch of documents.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-115">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-115">A new IndexBatch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch Merge (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch Merge(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.Document&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Merge(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.Document})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge (documents As IEnumerable(Of Document)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member Merge : seq&lt;Microsoft.Azure.Search.Models.Document&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.Merge documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt;" />
      </Parameters>
      <Docs>
        <param name="documents"><span data-ttu-id="38869-116">Die Dokumente zusammenführen; Legen Sie nur die Felder, die Sie ändern möchten.</span><span class="sxs-lookup"><span data-stu-id="38869-116">The documents to merge; Set only the fields that you want to change.</span></span></param>
        <summary>
            <span data-ttu-id="38869-117">Erstellt eine neue IndexBatch für das Zusammenführen von Dokumenten in vorhandenen Dokumente im Index.</span><span class="sxs-lookup"><span data-stu-id="38869-117">Creates a new IndexBatch for merging documents into existing documents in the index.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-118">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-118">A new IndexBatch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; Merge&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;T&gt; documents) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; Merge&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;!!T&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Merge``1(System.Collections.Generic.IEnumerable{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge(Of T As Class) (documents As IEnumerable(Of T)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member Merge : seq&lt;'T (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.Merge documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="38869-119">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="38869-119">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="38869-120">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="38869-120">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="documents"><span data-ttu-id="38869-121">Die Dokumente zusammenführen; Legen Sie nur die Eigenschaften, die Sie ändern möchten.</span><span class="sxs-lookup"><span data-stu-id="38869-121">The documents to merge; Set only the properties that you want to change.</span></span></param>
        <summary>
            <span data-ttu-id="38869-122">Erstellt eine neue IndexBatch für das Zusammenführen von Dokumenten in vorhandenen Dokumente im Index.</span><span class="sxs-lookup"><span data-stu-id="38869-122">Creates a new IndexBatch for merging documents into existing documents in the index.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-123">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-123">A new IndexBatch.</span></span></returns>
        <remarks>
            <span data-ttu-id="38869-124">Wenn Typ T NULL-Wert typisierte Eigenschaften enthält, können diese Eigenschaften nicht ordnungsgemäß zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="38869-124">If type T contains non-nullable value-typed properties, these properties may not merge correctly.</span></span> <span data-ttu-id="38869-125">Wenn Sie eine solche Eigenschaft nicht festgelegt, dauert es automatisch den Standardwert (z. B. 0 für Int) oder "false" für Bool, der den Wert der Eigenschaft, die derzeit im Index gespeicherten außer Kraft setzt, auch wenn dies nicht Ihre Absicht war.</span><span class="sxs-lookup"><span data-stu-id="38869-125">If you do not set such a property, it will automatically take its default value (for example, 0 for int or false for bool), which will override the value of the property currently stored in the index, even if this was not your intent.</span></span> <span data-ttu-id="38869-126">Aus diesem Grund wird dringend empfohlen, dass immer Deklarieren von Eigenschaften Wert eingegeben haben, um den Typ t auf NULL festgelegt werden</span><span class="sxs-lookup"><span data-stu-id="38869-126">For this reason, it is strongly recommended that you always declare value-typed properties to be nullable in type T.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch MergeOrUpload (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch MergeOrUpload(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.Document&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.MergeOrUpload(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.Document})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MergeOrUpload (documents As IEnumerable(Of Document)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : seq&lt;Microsoft.Azure.Search.Models.Document&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.MergeOrUpload documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt;" />
      </Parameters>
      <Docs>
        <param name="documents"><span data-ttu-id="38869-127">Die Dokumente zusammenführen oder hochladen.</span><span class="sxs-lookup"><span data-stu-id="38869-127">The documents to merge or upload.</span></span></param>
        <summary>
            <span data-ttu-id="38869-128">Erstellt eine neue IndexBatch für das Hochladen von Dokumenten, die dem Index oder in vorhandenen Dokumente zusammenführen für diejenigen, die bereits im Index vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="38869-128">Creates a new IndexBatch for uploading documents to the index, or merging them into existing documents for those that already exist in the index.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-129">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-129">A new IndexBatch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; MergeOrUpload&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;T&gt; documents) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; MergeOrUpload&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;!!T&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.MergeOrUpload``1(System.Collections.Generic.IEnumerable{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MergeOrUpload(Of T As Class) (documents As IEnumerable(Of T)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : seq&lt;'T (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.MergeOrUpload documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="38869-130">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="38869-130">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="38869-131">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="38869-131">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="documents"><span data-ttu-id="38869-132">Die Dokumente zusammenführen oder hochladen.</span><span class="sxs-lookup"><span data-stu-id="38869-132">The documents to merge or upload.</span></span></param>
        <summary>
            <span data-ttu-id="38869-133">Erstellt eine neue IndexBatch für das Hochladen von Dokumenten, die dem Index oder in vorhandenen Dokumente zusammenführen für diejenigen, die bereits im Index vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="38869-133">Creates a new IndexBatch for uploading documents to the index, or merging them into existing documents for those that already exist in the index.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-134">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-134">A new IndexBatch.</span></span></returns>
        <remarks>
            <span data-ttu-id="38869-135">Wenn Typ T NULL-Wert typisierte Eigenschaften enthält, können diese Eigenschaften nicht ordnungsgemäß zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="38869-135">If type T contains non-nullable value-typed properties, these properties may not merge correctly.</span></span> <span data-ttu-id="38869-136">Wenn Sie eine solche Eigenschaft nicht festgelegt, dauert es automatisch den Standardwert (z. B. 0 für Int) oder "false" für Bool, der den Wert der Eigenschaft, die derzeit im Index gespeicherten außer Kraft setzt, auch wenn dies nicht Ihre Absicht war.</span><span class="sxs-lookup"><span data-stu-id="38869-136">If you do not set such a property, it will automatically take its default value (for example, 0 for int or false for bool), which will override the value of the property currently stored in the index, even if this was not your intent.</span></span> <span data-ttu-id="38869-137">Aus diesem Grund wird dringend empfohlen, dass immer Deklarieren von Eigenschaften Wert eingegeben haben, um den Typ t auf NULL festgelegt werden</span><span class="sxs-lookup"><span data-stu-id="38869-137">For this reason, it is strongly recommended that you always declare value-typed properties to be nullable in type T.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="New">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch New (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&gt; actions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch New(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.IndexAction&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.New(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.IndexAction})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function New (actions As IEnumerable(Of IndexAction)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member New : seq&lt;Microsoft.Azure.Search.Models.IndexAction&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.New actions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actions" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&gt;" />
      </Parameters>
      <Docs>
        <param name="actions"><span data-ttu-id="38869-138">Die indexaktionen in den Batch aufgenommen werden soll.</span><span class="sxs-lookup"><span data-stu-id="38869-138">The index actions to include in the batch.</span></span></param>
        <summary>
            <span data-ttu-id="38869-139">Erstellt eine neue Instanz der Klasse IndexBatch an.</span><span class="sxs-lookup"><span data-stu-id="38869-139">Creates a new instance of the IndexBatch class.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-140">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-140">A new IndexBatch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="New&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; New&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;&gt; actions) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; New&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt;&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.New``1(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.IndexAction{``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function New(Of T As Class) (actions As IEnumerable(Of IndexAction(Of T))) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member New : seq&lt;Microsoft.Azure.Search.Models.IndexAction&lt;'T&gt;&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.New actions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actions" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="38869-141">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="38869-141">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="38869-142">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="38869-142">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="actions"><span data-ttu-id="38869-143">Die indexaktionen in den Batch aufgenommen werden soll.</span><span class="sxs-lookup"><span data-stu-id="38869-143">The index actions to include in the batch.</span></span></param>
        <summary>
            <span data-ttu-id="38869-144">Erstellt eine neue Instanz der Klasse IndexBatch an.</span><span class="sxs-lookup"><span data-stu-id="38869-144">Creates a new instance of the IndexBatch class.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-145">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-145">A new IndexBatch.</span></span></returns>
        <remarks>
            <span data-ttu-id="38869-146">Sie können diese Methode einen Schlüsselverweis verwenden, wenn Sie nicht explizit Ihrer Modellklasse wie ein Typparameter angeben möchten.</span><span class="sxs-lookup"><span data-stu-id="38869-146">You can use this method as a convenience if you don't want to explicitly specify your model class as a type parameter.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch Upload (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch Upload(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.Document&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Upload(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.Document})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Upload (documents As IEnumerable(Of Document)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member Upload : seq&lt;Microsoft.Azure.Search.Models.Document&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.Upload documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt;" />
      </Parameters>
      <Docs>
        <param name="documents"><span data-ttu-id="38869-147">Die Dokumente hochladen.</span><span class="sxs-lookup"><span data-stu-id="38869-147">The documents to upload.</span></span></param>
        <summary>
            <span data-ttu-id="38869-148">Erstellt eine neue IndexBatch für das Hochladen von Dokumenten, die dem Index.</span><span class="sxs-lookup"><span data-stu-id="38869-148">Creates a new IndexBatch for uploading documents to the index.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-149">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-149">A new IndexBatch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; Upload&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;T&gt; documents) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; Upload&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;!!T&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Upload``1(System.Collections.Generic.IEnumerable{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Upload(Of T As Class) (documents As IEnumerable(Of T)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member Upload : seq&lt;'T (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.Upload documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="38869-150">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="38869-150">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="38869-151">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="38869-151">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="documents"><span data-ttu-id="38869-152">Die Dokumente hochladen.</span><span class="sxs-lookup"><span data-stu-id="38869-152">The documents to upload.</span></span></param>
        <summary>
            <span data-ttu-id="38869-153">Erstellt eine neue IndexBatch für das Hochladen von Dokumenten, die dem Index.</span><span class="sxs-lookup"><span data-stu-id="38869-153">Creates a new IndexBatch for uploading documents to the index.</span></span>
            </summary>
        <returns><span data-ttu-id="38869-154">Eine neue IndexBatch.</span><span class="sxs-lookup"><span data-stu-id="38869-154">A new IndexBatch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>