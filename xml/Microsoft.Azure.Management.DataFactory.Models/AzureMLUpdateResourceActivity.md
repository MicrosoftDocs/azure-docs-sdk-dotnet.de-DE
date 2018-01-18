<Type Name="AzureMLUpdateResourceActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity">
  <TypeSignature Language="C#" Value="public class AzureMLUpdateResourceActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLUpdateResourceActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLUpdateResourceActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type AzureMLUpdateResourceActivity = class&#xA;    inherit ExecutionActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AzureMLUpdateResource")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="90bb4-101">Azure ML Update Ressource Management-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="90bb4-101">Azure ML Update Resource management activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLUpdateResourceActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="90bb4-102">Initialisiert eine neue Instanz der AzureMLUpdateResourceActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="90bb4-102">Initializes a new instance of the AzureMLUpdateResourceActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLUpdateResourceActivity (string name, object trainedModelName, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference trainedModelLinkedServiceName, object trainedModelFilePath, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object trainedModelName, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference trainedModelLinkedServiceName, object trainedModelFilePath, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.#ctor(System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, trainedModelName As Object, trainedModelLinkedServiceName As LinkedServiceReference, trainedModelFilePath As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity : string * obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity (name, trainedModelName, trainedModelLinkedServiceName, trainedModelFilePath, additionalProperties, description, dependsOn, linkedServiceName, policy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="trainedModelName" Type="System.Object" />
        <Parameter Name="trainedModelLinkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="trainedModelFilePath" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="90bb4-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="90bb4-103">Activity name.</span></span></param>
        <param name="trainedModelName"><span data-ttu-id="90bb4-104">Namen des Trained Model-Moduls in dem webdienstexperiment aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="90bb4-104">Name of the Trained Model module in the Web Service experiment to be updated.</span></span> <span data-ttu-id="90bb4-105">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="90bb4-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="trainedModelLinkedServiceName"><span data-ttu-id="90bb4-106">Name des Azure-Speicher verknüpfter Dienst, die mit der .ilearner-Datei, die durch den Aktualisierungsvorgang hochgeladen werden.</span><span class="sxs-lookup"><span data-stu-id="90bb4-106">Name of Azure Storage linked service holding the .ilearner file that will be uploaded by the update operation.</span></span></param>
        <param name="trainedModelFilePath"><span data-ttu-id="90bb4-107">Den relativen Dateipfad in TrainedModelLinkedService .ilearner Datei darstellt, die durch den Aktualisierungsvorgang hochgeladen wird.</span><span class="sxs-lookup"><span data-stu-id="90bb4-107">The relative file path in trainedModelLinkedService to represent the .ilearner file that will be uploaded by the update operation.</span></span>  <span data-ttu-id="90bb4-108">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="90bb4-108">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="90bb4-109">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="90bb4-109">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="90bb4-110">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="90bb4-110">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="90bb4-111">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="90bb4-111">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="90bb4-112">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="90bb4-112">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="90bb4-113">"Aktivitätsrichtlinie".</span><span class="sxs-lookup"><span data-stu-id="90bb4-113">Activity policy.</span></span></param>
        <summary>
            <span data-ttu-id="90bb4-114">Initialisiert eine neue Instanz der AzureMLUpdateResourceActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="90bb4-114">Initializes a new instance of the AzureMLUpdateResourceActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrainedModelFilePath">
      <MemberSignature Language="C#" Value="public object TrainedModelFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrainedModelFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrainedModelFilePath As Object" />
      <MemberSignature Language="F#" Value="member this.TrainedModelFilePath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.trainedModelFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90bb4-115">Ruft ein, oder legt den relativen Pfad in TrainedModelLinkedService .ilearner Datei darstellt, die durch den Aktualisierungsvorgang hochgeladen wird.</span><span class="sxs-lookup"><span data-stu-id="90bb4-115">Gets or sets the relative file path in trainedModelLinkedService to represent the .ilearner file that will be uploaded by the update operation.</span></span>  <span data-ttu-id="90bb4-116">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="90bb4-116">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrainedModelLinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference TrainedModelLinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference TrainedModelLinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelLinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property TrainedModelLinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.TrainedModelLinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelLinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.trainedModelLinkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90bb4-117">Ruft ab oder legt Name des verknüpften Azure Storage-Diensts, halten die .ilearner-Datei, die durch den Aktualisierungsvorgang hochgeladen werden.</span><span class="sxs-lookup"><span data-stu-id="90bb4-117">Gets or sets name of Azure Storage linked service holding the .ilearner file that will be uploaded by the update operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrainedModelName">
      <MemberSignature Language="C#" Value="public object TrainedModelName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrainedModelName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelName" />
      <MemberSignature Language="VB.NET" Value="Public Property TrainedModelName As Object" />
      <MemberSignature Language="F#" Value="member this.TrainedModelName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.trainedModelName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90bb4-118">Ruft ab oder legt die Namen des Trained Model-Moduls in dem webdienstexperiment aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="90bb4-118">Gets or sets name of the Trained Model module in the Web Service experiment to be updated.</span></span> <span data-ttu-id="90bb4-119">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="90bb4-119">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureMLUpdateResourceActivity.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="90bb4-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="90bb4-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="90bb4-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="90bb4-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>