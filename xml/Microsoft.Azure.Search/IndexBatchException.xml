<Type Name="IndexBatchException" FullName="Microsoft.Azure.Search.IndexBatchException">
  <TypeSignature Language="C#" Value="public class IndexBatchException : Microsoft.Rest.Azure.CloudException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexBatchException extends Microsoft.Rest.Azure.CloudException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IndexBatchException" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexBatchException&#xA;Inherits CloudException" />
  <TypeSignature Language="F#" Value="type IndexBatchException = class&#xA;    inherit CloudException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.Azure.CloudException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6e549-101">Die Ausnahme wird ausgelöst, wenn ein Indizierungsvorgangs nur teilweise erfolgreich ist.</span><span class="sxs-lookup"><span data-stu-id="6e549-101">Exception thrown when an indexing operation only partially succeeds.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexBatchException (Microsoft.Azure.Search.Models.DocumentIndexResult documentIndexResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Search.Models.DocumentIndexResult documentIndexResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexBatchException.#ctor(Microsoft.Azure.Search.Models.DocumentIndexResult)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.IndexBatchException : Microsoft.Azure.Search.Models.DocumentIndexResult -&gt; Microsoft.Azure.Search.IndexBatchException" Usage="new Microsoft.Azure.Search.IndexBatchException documentIndexResult" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="documentIndexResult" Type="Microsoft.Azure.Search.Models.DocumentIndexResult" />
      </Parameters>
      <Docs>
        <param name="documentIndexResult"><span data-ttu-id="6e549-102">Die deserialisierte Antwort aus dem Index-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6e549-102">The deserialized response from the index request.</span></span></param>
        <summary>
            <span data-ttu-id="6e549-103">Initialisiert eine neue Instanz der IndexBatchException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e549-103">Initializes a new instance of the IndexBatchException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindFailedActionsToRetry">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexBatch FindFailedActionsToRetry (Microsoft.Azure.Search.Models.IndexBatch originalBatch, string keyFieldName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Search.Models.IndexBatch FindFailedActionsToRetry(class Microsoft.Azure.Search.Models.IndexBatch originalBatch, string keyFieldName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexBatchException.FindFailedActionsToRetry(Microsoft.Azure.Search.Models.IndexBatch,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FindFailedActionsToRetry (originalBatch As IndexBatch, keyFieldName As String) As IndexBatch" />
      <MemberSignature Language="F#" Value="member this.FindFailedActionsToRetry : Microsoft.Azure.Search.Models.IndexBatch * string -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="indexBatchException.FindFailedActionsToRetry (originalBatch, keyFieldName)" />
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
        <Parameter Name="originalBatch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="keyFieldName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originalBatch"><span data-ttu-id="6e549-104">Der Batch, der teilweise Indizierung fehlgeschlagenen.</span><span class="sxs-lookup"><span data-stu-id="6e549-104">The batch that partially failed indexing.</span></span></param>
        <param name="keyFieldName"><span data-ttu-id="6e549-105">Der Name des Schlüsselfelds aus dem IndexSchema.</span><span class="sxs-lookup"><span data-stu-id="6e549-105">The name of the key field from the index schema.</span></span></param>
        <summary>
            <span data-ttu-id="6e549-106">Sucht alle Aktionen im angegebenen Batch, die Fehler und muss wiederholt werden, und gibt diese in einen neuen Batch zurück.</span><span class="sxs-lookup"><span data-stu-id="6e549-106">Finds all index actions in the given batch that failed and need to be retried, and returns them in a new batch.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6e549-107">Einen neuen Batch, enthält alle Aktionen, die aus dem angegebenen Batch, der Fehler und wiederholt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="6e549-107">A new batch containing all the actions from the given batch that failed and should be retried.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindFailedActionsToRetry&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; FindFailedActionsToRetry&lt;T&gt; (Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; originalBatch, Func&lt;T,string&gt; keySelector) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; FindFailedActionsToRetry&lt;class T&gt;(class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; originalBatch, class System.Func`2&lt;!!T, string&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexBatchException.FindFailedActionsToRetry``1(Microsoft.Azure.Search.Models.IndexBatch{``0},System.Func{``0,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function FindFailedActionsToRetry(Of T As Class) (originalBatch As IndexBatch(Of T), keySelector As Func(Of T, String)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="member this.FindFailedActionsToRetry : Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Func&lt;'T, string (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="indexBatchException.FindFailedActionsToRetry (originalBatch, keySelector)" />
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
        <Parameter Name="originalBatch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="keySelector" Type="System.Func&lt;T,System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="6e549-108">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6e549-108">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="6e549-109">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="6e549-109">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="originalBatch"><span data-ttu-id="6e549-110">Der Batch, der teilweise Indizierung fehlgeschlagenen.</span><span class="sxs-lookup"><span data-stu-id="6e549-110">The batch that partially failed indexing.</span></span></param>
        <param name="keySelector"><span data-ttu-id="6e549-111">Ein Lambda-Ausdruck, der einen Schlüsselwert aus einem bestimmten Dokument vom Typ t abruft</span><span class="sxs-lookup"><span data-stu-id="6e549-111">A lambda that retrieves a key value from a given document of type T.</span></span></param>
        <summary>
            <span data-ttu-id="6e549-112">Sucht alle Aktionen im angegebenen Batch, die Fehler und muss wiederholt werden, und gibt diese in einen neuen Batch zurück.</span><span class="sxs-lookup"><span data-stu-id="6e549-112">Finds all index actions in the given batch that failed and need to be retried, and returns them in a new batch.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6e549-113">Einen neuen Batch, enthält alle Aktionen, die aus dem angegebenen Batch, der Fehler und wiederholt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="6e549-113">A new batch containing all the actions from the given batch that failed and should be retried.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexingResults">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt; IndexingResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.IndexingResult&gt; IndexingResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexingResults As IList(Of IndexingResult)" />
      <MemberSignature Language="F#" Value="member this.IndexingResults : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt;" Usage="Microsoft.Azure.Search.IndexBatchException.IndexingResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e549-114">Ruft die Ergebnisse für den Index-Batch, der den Status für jede einzelne Index-Aktion enthält.</span><span class="sxs-lookup"><span data-stu-id="6e549-114">Gets the results for the index batch that contains the status for each individual index action.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>