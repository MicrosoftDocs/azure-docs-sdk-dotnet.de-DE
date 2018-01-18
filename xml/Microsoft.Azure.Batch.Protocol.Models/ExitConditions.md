<Type Name="ExitConditions" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitConditions">
  <TypeSignature Language="C#" Value="public class ExitConditions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitConditions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitConditions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitConditions" />
  <TypeSignature Language="F#" Value="type ExitConditions = class" />
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
            <span data-ttu-id="12971-101">Gibt an, wie der Batch-Dienst reagieren soll, wenn die Aufgabe abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="12971-101">Specifies how the Batch service should respond when the task completes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitConditions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.#ctor" />
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
            <span data-ttu-id="12971-102">Initialisiert eine neue Instanz der ExitConditions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="12971-102">Initializes a new instance of the ExitConditions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitConditions (System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; exitCodes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; exitCodeRanges = null, Microsoft.Azure.Batch.Protocol.Models.ExitOptions preProcessingError = null, Microsoft.Azure.Batch.Protocol.Models.ExitOptions fileUploadError = null, Microsoft.Azure.Batch.Protocol.Models.ExitOptions defaultProperty = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; exitCodes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; exitCodeRanges, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions preProcessingError, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions fileUploadError, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions defaultProperty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping},Microsoft.Azure.Batch.Protocol.Models.ExitOptions,Microsoft.Azure.Batch.Protocol.Models.ExitOptions,Microsoft.Azure.Batch.Protocol.Models.ExitOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional exitCodes As IList(Of ExitCodeMapping) = null, Optional exitCodeRanges As IList(Of ExitCodeRangeMapping) = null, Optional preProcessingError As ExitOptions = null, Optional fileUploadError As ExitOptions = null, Optional defaultProperty As ExitOptions = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitConditions : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; * Microsoft.Azure.Batch.Protocol.Models.ExitOptions * Microsoft.Azure.Batch.Protocol.Models.ExitOptions * Microsoft.Azure.Batch.Protocol.Models.ExitOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitConditions" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitConditions (exitCodes, exitCodeRanges, preProcessingError, fileUploadError, defaultProperty)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exitCodes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt;" />
        <Parameter Name="exitCodeRanges" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt;" />
        <Parameter Name="preProcessingError" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
        <Parameter Name="fileUploadError" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
        <Parameter Name="defaultProperty" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="exitCodes"><span data-ttu-id="12971-103">Eine Liste der einzelnen Vorgang Exitcodes und wie der Batch-Dienst auf diese reagieren soll.</span><span class="sxs-lookup"><span data-stu-id="12971-103">A list of individual task exit codes and how the Batch service should respond to them.</span></span></param>
        <param name="exitCodeRanges"><span data-ttu-id="12971-104">Eine Liste der Aufgabe beenden Code Bereiche und wie der Batch-Dienst auf diese reagieren soll.</span><span class="sxs-lookup"><span data-stu-id="12971-104">A list of task exit code ranges and how the Batch service should respond to them.</span></span></param>
        <param name="preProcessingError"><span data-ttu-id="12971-105">Wie der Batch-Dienst reagieren soll, wenn der Task fehlschlägt, wurde aufgrund eines Fehlers nicht gestartet.</span><span class="sxs-lookup"><span data-stu-id="12971-105">How the Batch service should respond if the task fails to start due to an error.</span></span></param>
        <param name="fileUploadError"><span data-ttu-id="12971-106">Wie der Batch-Dienst reagieren soll, wenn ein Datei hochladen-Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="12971-106">How the Batch service should respond if a file upload error occurs.</span></span></param>
        <param name="defaultProperty"><span data-ttu-id="12971-107">Wie der Batch-Dienst reagieren soll, wenn der Task, mit der eine beenden-Bedingung, die nicht durch eine der anderen Eigenschaften abgedeckt fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="12971-107">How the Batch service should respond if the task fails with an exit condition not covered by any of the other properties.</span></span></param>
        <summary>
            <span data-ttu-id="12971-108">Initialisiert eine neue Instanz der ExitConditions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="12971-108">Initializes a new instance of the ExitConditions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions DefaultProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions DefaultProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.DefaultProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultProperty As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultProperty : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.DefaultProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="default")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12971-109">Ruft ab oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn der Task, mit der eine beenden-Bedingung, die nicht durch eine der anderen Eigenschaften abgedeckt fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="12971-109">Gets or sets how the Batch service should respond if the task fails with an exit condition not covered by any of the other properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="12971-110">Dieser Wert wird verwendet, wenn die Aufgabe beendet alle Exitcode, die nicht in der Auflistung ExitCodes oder ExitCodeRanges aufgeführt, mit Fehler vor der Verarbeitung, wenn die PreProcessingError-Eigenschaft nicht vorhanden ist oder mit einem Fehler beim Dateiupload wird, wenn die FileUploadError-Eigenschaft nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="12971-110">This value is used if the task exits with any nonzero exit code not listed in the exitCodes or exitCodeRanges collection, with a pre-processing error if the preProcessingError property is not present, or with a file upload error if the fileUploadError property is not present.</span></span> <span data-ttu-id="12971-111">Wenn Sie nicht standardmäßige Verhalten in den Exitcode 0 möchten, müssen Sie explizit mithilfe der Auflistung ExitCodes oder ExitCodeRanges auflisten.</span><span class="sxs-lookup"><span data-stu-id="12971-111">If you want non-default behaviour on exit code 0, you must list it explicitly using the exitCodes or exitCodeRanges collection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodeRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; ExitCodeRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; ExitCodeRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodeRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodeRanges As IList(Of ExitCodeRangeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodeRanges : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodeRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCodeRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12971-112">Ruft ab oder legt eine Liste der Aufgabe beenden Code Bereiche und wie der Batch-Dienst auf diese reagieren soll.</span><span class="sxs-lookup"><span data-stu-id="12971-112">Gets or sets a list of task exit code ranges and how the Batch service should respond to them.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; ExitCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; ExitCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodes As IList(Of ExitCodeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12971-113">Ruft ab oder legt eine Liste der einzelnen Vorgang Exitcodes und wie der Batch-Dienst auf diese reagieren soll.</span><span class="sxs-lookup"><span data-stu-id="12971-113">Gets or sets a list of individual task exit codes and how the Batch service should respond to them.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileUploadError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions FileUploadError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions FileUploadError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.FileUploadError" />
      <MemberSignature Language="VB.NET" Value="Public Property FileUploadError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.FileUploadError : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.FileUploadError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileUploadError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12971-114">Ruft ab, oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn ein Datei hochladen-Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="12971-114">Gets or sets how the Batch service should respond if a file upload error occurs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="12971-115">Wenn der Task mit dem Exitcode, die über ExitCodes oder ExitCodeRanges angegeben wurde beendet, und klicken Sie dann einen Datei hochladen-Fehler aufgetreten, hat die Aktion, die gemäß des Exitcodes Vorrang vor.</span><span class="sxs-lookup"><span data-stu-id="12971-115">If the task exited with an exit code that was specified via exitCodes or exitCodeRanges, and then encountered a file upload error, then the action specified by the exit code takes precedence.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreProcessingError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions PreProcessingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions PreProcessingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.PreProcessingError" />
      <MemberSignature Language="VB.NET" Value="Public Property PreProcessingError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.PreProcessingError : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.PreProcessingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preProcessingError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12971-116">Ruft ab oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn der Task fehlschlägt, wurde aufgrund eines Fehlers nicht gestartet.</span><span class="sxs-lookup"><span data-stu-id="12971-116">Gets or sets how the Batch service should respond if the task fails to start due to an error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>