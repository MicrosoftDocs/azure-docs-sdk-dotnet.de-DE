<Type Name="IndexAction" FullName="Microsoft.Azure.Search.Models.IndexAction">
  <TypeSignature Language="C#" Value="public class IndexAction : Microsoft.Azure.Search.Models.IndexActionBase&lt;Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexAction extends Microsoft.Azure.Search.Models.IndexActionBase`1&lt;class Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexAction" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexAction&#xA;Inherits IndexActionBase(Of Document)" />
  <TypeSignature Language="F#" Value="type IndexAction = class&#xA;    inherit IndexActionBase&lt;Document&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.IndexActionBase&lt;Microsoft.Azure.Search.Models.Document&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.Document</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0133-101">Stellt eine Index-Aktion, die für ein Dokument ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c0133-101">Represents an index action that operates on a document.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Delete (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Delete(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Delete(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Delete document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document"><span data-ttu-id="c0133-102">Das zu löschende Dokument; Felder als die Schlüssel werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="c0133-102">The document to delete; Fields other than the key are ignored.</span></span></param>
        <summary>
            <span data-ttu-id="c0133-103">Erstellt eine neue IndexAction für das Löschen eines Dokuments an.</span><span class="sxs-lookup"><span data-stu-id="c0133-103">Creates a new IndexAction for deleting a document.</span></span>
            </summary>
        <returns><span data-ttu-id="c0133-104">Eine neue IndexAction.</span><span class="sxs-lookup"><span data-stu-id="c0133-104">A new IndexAction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Delete (string keyName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Delete(string keyName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Delete(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (keyName As String, keyValue As String) As IndexAction" />
      <MemberSignature Language="F#" Value="static member Delete : string * string -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Delete (keyName, keyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="c0133-105">Der Name des Schlüsselfelds des Indexes.</span><span class="sxs-lookup"><span data-stu-id="c0133-105">The name of the key field of the index.</span></span></param>
        <param name="keyValue"><span data-ttu-id="c0133-106">Der Schlüssel des Dokuments zu löschen.</span><span class="sxs-lookup"><span data-stu-id="c0133-106">The key of the document to delete.</span></span></param>
        <summary>
            <span data-ttu-id="c0133-107">Erstellt eine neue IndexAction für das Löschen eines Dokuments an.</span><span class="sxs-lookup"><span data-stu-id="c0133-107">Creates a new IndexAction for deleting a document.</span></span>
            </summary>
        <returns><span data-ttu-id="c0133-108">Eine neue IndexAction.</span><span class="sxs-lookup"><span data-stu-id="c0133-108">A new IndexAction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; Delete&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; Delete&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Delete``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member Delete : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.Delete document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="c0133-109">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c0133-109">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="c0133-110">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="c0133-110">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="document"><span data-ttu-id="c0133-111">Das zu löschende Dokument; Felder als die Schlüssel werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="c0133-111">The document to delete; Fields other than the key are ignored.</span></span></param>
        <summary>
            <span data-ttu-id="c0133-112">Erstellt eine neue IndexAction für das Löschen eines Dokuments an.</span><span class="sxs-lookup"><span data-stu-id="c0133-112">Creates a new IndexAction for deleting a document.</span></span>
            </summary>
        <returns><span data-ttu-id="c0133-113">Eine neue IndexAction.</span><span class="sxs-lookup"><span data-stu-id="c0133-113">A new IndexAction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Merge (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Merge(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Merge(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member Merge : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Merge document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document"><span data-ttu-id="c0133-114">Das Dokument zum Zusammenführen; Legen Sie nur die Felder, die Sie ändern möchten.</span><span class="sxs-lookup"><span data-stu-id="c0133-114">The document to merge; Set only the fields that you want to change.</span></span></param>
        <summary>
            <span data-ttu-id="c0133-115">Erstellt eine neue IndexAction für das Zusammenführen ein Dokument in ein vorhandenes Dokument im Index.</span><span class="sxs-lookup"><span data-stu-id="c0133-115">Creates a new IndexAction for merging a document into an existing document in the index.</span></span>
            </summary>
        <returns><span data-ttu-id="c0133-116">Eine neue IndexAction.</span><span class="sxs-lookup"><span data-stu-id="c0133-116">A new IndexAction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; Merge&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; Merge&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Merge``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member Merge : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.Merge document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="c0133-117">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c0133-117">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="c0133-118">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="c0133-118">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="document"><span data-ttu-id="c0133-119">Das Dokument zum Zusammenführen; Legen Sie nur die Eigenschaften, die Sie ändern möchten.</span><span class="sxs-lookup"><span data-stu-id="c0133-119">The document to merge; Set only the properties that you want to change.</span></span></param>
        <summary>
            <span data-ttu-id="c0133-120">Erstellt eine neue IndexAction für das Zusammenführen ein Dokument in ein vorhandenes Dokument im Index.</span><span class="sxs-lookup"><span data-stu-id="c0133-120">Creates a new IndexAction for merging a document into an existing document in the index.</span></span>
            </summary>
        <returns><span data-ttu-id="c0133-121">Eine neue IndexAction.</span><span class="sxs-lookup"><span data-stu-id="c0133-121">A new IndexAction.</span></span></returns>
        <remarks>
            <span data-ttu-id="c0133-122">Wenn Typ T NULL-Wert typisierte Eigenschaften enthält, können diese Eigenschaften nicht ordnungsgemäß zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="c0133-122">If type T contains non-nullable value-typed properties, these properties may not merge correctly.</span></span> <span data-ttu-id="c0133-123">Wenn Sie eine solche Eigenschaft nicht festgelegt, dauert es automatisch den Standardwert (z. B. 0 für Int) oder "false" für Bool, der den Wert der Eigenschaft, die derzeit im Index gespeicherten außer Kraft setzt, auch wenn dies nicht Ihre Absicht war.</span><span class="sxs-lookup"><span data-stu-id="c0133-123">If you do not set such a property, it will automatically take its default value (for example, 0 for int or false for bool), which will override the value of the property currently stored in the index, even if this was not your intent.</span></span> <span data-ttu-id="c0133-124">Aus diesem Grund wird dringend empfohlen, dass immer Deklarieren von Eigenschaften Wert eingegeben haben, um den Typ t auf NULL festgelegt werden</span><span class="sxs-lookup"><span data-stu-id="c0133-124">For this reason, it is strongly recommended that you always declare value-typed properties to be nullable in type T.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction MergeOrUpload (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction MergeOrUpload(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document"><span data-ttu-id="c0133-125">Das Dokument, merge oder hochladen.</span><span class="sxs-lookup"><span data-stu-id="c0133-125">The document to merge or upload.</span></span></param>
        <summary>
            <span data-ttu-id="c0133-126">Erstellt eine neue IndexAction für Hochladen eines Dokuments, die dem Index oder in einem vorhandenen Dokument zusammenführen, wenn sie bereits im Index vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c0133-126">Creates a new IndexAction for uploading a document to the index, or merging it into an existing document if it already exists in the index.</span></span>
            </summary>
        <returns><span data-ttu-id="c0133-127">Eine neue IndexAction.</span><span class="sxs-lookup"><span data-stu-id="c0133-127">A new IndexAction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; MergeOrUpload&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; MergeOrUpload&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MergeOrUpload(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="c0133-128">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c0133-128">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="c0133-129">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="c0133-129">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="document"><span data-ttu-id="c0133-130">Das Dokument, merge oder hochladen.</span><span class="sxs-lookup"><span data-stu-id="c0133-130">The document to merge or upload.</span></span></param>
        <summary>
            <span data-ttu-id="c0133-131">Erstellt eine neue IndexAction für Hochladen eines Dokuments, die dem Index oder in einem vorhandenen Dokument zusammenführen, wenn sie bereits im Index vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c0133-131">Creates a new IndexAction for uploading a document to the index, or merging it into an existing document if it already exists in the index.</span></span>
            </summary>
        <returns><span data-ttu-id="c0133-132">Eine neue IndexAction.</span><span class="sxs-lookup"><span data-stu-id="c0133-132">A new IndexAction.</span></span></returns>
        <remarks>
            <span data-ttu-id="c0133-133">Wenn Typ T NULL-Wert typisierte Eigenschaften enthält, können diese Eigenschaften nicht ordnungsgemäß zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="c0133-133">If type T contains non-nullable value-typed properties, these properties may not merge correctly.</span></span> <span data-ttu-id="c0133-134">Wenn Sie eine solche Eigenschaft nicht festgelegt, dauert es automatisch den Standardwert (z. B. 0 für Int) oder "false" für Bool, der den Wert der Eigenschaft, die derzeit im Index gespeicherten außer Kraft setzt, auch wenn dies nicht Ihre Absicht war.</span><span class="sxs-lookup"><span data-stu-id="c0133-134">If you do not set such a property, it will automatically take its default value (for example, 0 for int or false for bool), which will override the value of the property currently stored in the index, even if this was not your intent.</span></span> <span data-ttu-id="c0133-135">Aus diesem Grund wird dringend empfohlen, dass immer Deklarieren von Eigenschaften Wert eingegeben haben, um den Typ t auf NULL festgelegt werden</span><span class="sxs-lookup"><span data-stu-id="c0133-135">For this reason, it is strongly recommended that you always declare value-typed properties to be nullable in type T.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Upload (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Upload(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Upload(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member Upload : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Upload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document"><span data-ttu-id="c0133-136">Das Dokument hochladen.</span><span class="sxs-lookup"><span data-stu-id="c0133-136">The document to upload.</span></span></param>
        <summary>
            <span data-ttu-id="c0133-137">Erstellt eine neue IndexAction zum Hochladen eines Dokuments, die dem Index.</span><span class="sxs-lookup"><span data-stu-id="c0133-137">Creates a new IndexAction for uploading a document to the index.</span></span>
            </summary>
        <returns><span data-ttu-id="c0133-138">Eine neue IndexAction.</span><span class="sxs-lookup"><span data-stu-id="c0133-138">A new IndexAction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; Upload&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; Upload&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Upload``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Upload(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member Upload : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.Upload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="c0133-139">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c0133-139">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="c0133-140">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="c0133-140">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="document"><span data-ttu-id="c0133-141">Das Dokument hochladen.</span><span class="sxs-lookup"><span data-stu-id="c0133-141">The document to upload.</span></span></param>
        <summary>
            <span data-ttu-id="c0133-142">Erstellt eine neue IndexAction zum Hochladen eines Dokuments, die dem Index.</span><span class="sxs-lookup"><span data-stu-id="c0133-142">Creates a new IndexAction for uploading a document to the index.</span></span>
            </summary>
        <returns><span data-ttu-id="c0133-143">Eine neue IndexAction.</span><span class="sxs-lookup"><span data-stu-id="c0133-143">A new IndexAction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>