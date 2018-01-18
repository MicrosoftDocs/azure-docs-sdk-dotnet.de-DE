<Type Name="JobSchedulingError" FullName="Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError">
  <TypeSignature Language="C#" Value="public class JobSchedulingError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobSchedulingError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSchedulingError" />
  <TypeSignature Language="F#" Value="type JobSchedulingError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9e343-101">Ein Fehler vom Batch-Dienst beim Planen eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="9e343-101">An error encountered by the Batch service when scheduling a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSchedulingError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9e343-102">Initialisiert eine neue Instanz der JobSchedulingError-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9e343-102">Initializes a new instance of the JobSchedulingError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSchedulingError (Microsoft.Azure.Batch.Protocol.Models.ErrorCategory category, string code = null, string message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.ErrorCategory category, string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.#ctor(Microsoft.Azure.Batch.Protocol.Models.ErrorCategory,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.NameValuePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (category As ErrorCategory, Optional code As String = null, Optional message As String = null, Optional details As IList(Of NameValuePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError : Microsoft.Azure.Batch.Protocol.Models.ErrorCategory * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError (category, code, message, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="category" Type="Microsoft.Azure.Batch.Protocol.Models.ErrorCategory" />
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;" />
      </Parameters>
      <Docs>
        <param name="category"><span data-ttu-id="9e343-103">Die Kategorie des Auftrags Planungsfehler.</span><span class="sxs-lookup"><span data-stu-id="9e343-103">The category of the job scheduling error.</span></span></param>
        <param name="code"><span data-ttu-id="9e343-104">Ein Bezeichner für die auftragsplanung-Fehler.</span><span class="sxs-lookup"><span data-stu-id="9e343-104">An identifier for the job scheduling error.</span></span>
            <span data-ttu-id="9e343-105">Codes sind unveränderlich und programmgesteuert genutzt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="9e343-105">Codes are invariant and are intended to be consumed programmatically.</span></span></param>
        <param name="message"><span data-ttu-id="9e343-106">Eine Meldung mit einer Beschreibung der auftragsplanung Fehler vorgesehen, eignet sich für die Anzeige in einer Benutzeroberfläche.</span><span class="sxs-lookup"><span data-stu-id="9e343-106">A message describing the job scheduling error, intended to be suitable for display in a user interface.</span></span></param>
        <param name="details"><span data-ttu-id="9e343-107">Eine Liste mit zusätzlichen Fehlerinformationen zum Planungsfehler.</span><span class="sxs-lookup"><span data-stu-id="9e343-107">A list of additional error details related to the scheduling error.</span></span></param>
        <summary>
            <span data-ttu-id="9e343-108">Initialisiert eine neue Instanz der JobSchedulingError-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9e343-108">Initializes a new instance of the JobSchedulingError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ErrorCategory Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.ErrorCategory Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As ErrorCategory" />
      <MemberSignature Language="F#" Value="member this.Category : Microsoft.Azure.Batch.Protocol.Models.ErrorCategory with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ErrorCategory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e343-109">Ruft ab oder legt die Kategorie des Auftrags Planungsfehler.</span><span class="sxs-lookup"><span data-stu-id="9e343-109">Gets or sets the category of the job scheduling error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9e343-110">Folgende Werte sind möglich: "UserError", "ServerError"</span><span class="sxs-lookup"><span data-stu-id="9e343-110">Possible values include: 'userError', 'serverError'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e343-111">Ruft ab oder legt einen Bezeichner für die auftragsplanung-Fehler.</span><span class="sxs-lookup"><span data-stu-id="9e343-111">Gets or sets an identifier for the job scheduling error.</span></span> <span data-ttu-id="9e343-112">Codes sind unveränderlich und programmgesteuert genutzt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="9e343-112">Codes are invariant and are intended to be consumed programmatically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e343-113">Ruft ab oder legt eine Liste der zusätzliche Fehlerinformationen zum Planungsfehler.</span><span class="sxs-lookup"><span data-stu-id="9e343-113">Gets or sets a list of additional error details related to the scheduling error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e343-114">Ruft ab oder legt eine Meldung mit einer Beschreibung der auftragsplanung Fehler, die für die Anzeige in einer Benutzeroberfläche geeignet sein soll.</span><span class="sxs-lookup"><span data-stu-id="9e343-114">Gets or sets a message describing the job scheduling error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobSchedulingError.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9e343-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e343-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9e343-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9e343-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>