<Type Name="GetMetadataActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity">
  <TypeSignature Language="C#" Value="public class GetMetadataActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GetMetadataActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class GetMetadataActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type GetMetadataActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("GetMetadata")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="dd0ad-101">Aktivität zum Abrufen von Metadaten des Datasets</span><span class="sxs-lookup"><span data-stu-id="dd0ad-101">Activity to get metadata of dataset</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetMetadataActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity.#ctor" />
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
            <span data-ttu-id="dd0ad-102">Initialisiert eine neue Instanz der GetMetadataActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-102">Initializes a new instance of the GetMetadataActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetMetadataActivity (string name, Microsoft.Azure.Management.DataFactory.Models.DatasetReference dataset, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, System.Collections.Generic.IList&lt;object&gt; fieldList = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactory.Models.DatasetReference dataset, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class System.Collections.Generic.IList`1&lt;object&gt; fieldList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity.#ctor(System.String,Microsoft.Azure.Management.DataFactory.Models.DatasetReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Collections.Generic.IList{System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, dataset As DatasetReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional fieldList As IList(Of Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity : string * Microsoft.Azure.Management.DataFactory.Models.DatasetReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * System.Collections.Generic.IList&lt;obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity (name, dataset, additionalProperties, description, dependsOn, linkedServiceName, policy, fieldList)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="dataset" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="fieldList" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="dd0ad-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-103">Activity name.</span></span></param>
        <param name="dataset"><span data-ttu-id="dd0ad-104">Datasetverweis GetMetadata-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-104">GetMetadata activity dataset reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="dd0ad-105">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="dd0ad-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="dd0ad-106">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-106">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="dd0ad-107">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-107">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="dd0ad-108">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-108">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="dd0ad-109">"Aktivitätsrichtlinie".</span><span class="sxs-lookup"><span data-stu-id="dd0ad-109">Activity policy.</span></span></param>
        <param name="fieldList"><span data-ttu-id="dd0ad-110">Felder von Metadaten aus dem Dataset abgerufen.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-110">Fields of metadata to get from dataset.</span></span></param>
        <summary>
            <span data-ttu-id="dd0ad-111">Initialisiert eine neue Instanz der GetMetadataActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-111">Initializes a new instance of the GetMetadataActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dataset">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetReference Dataset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetReference Dataset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity.Dataset" />
      <MemberSignature Language="VB.NET" Value="Public Property Dataset As DatasetReference" />
      <MemberSignature Language="F#" Value="member this.Dataset : Microsoft.Azure.Management.DataFactory.Models.DatasetReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity.Dataset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.dataset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd0ad-112">Ruft ab, oder legt ihn fest GetMetadata Aktivität Datasetverweis.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-112">Gets or sets getMetadata activity dataset reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FieldList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; FieldList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; FieldList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity.FieldList" />
      <MemberSignature Language="VB.NET" Value="Public Property FieldList As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.FieldList : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity.FieldList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.fieldList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd0ad-113">Abrufen oder Festlegen von Metadaten aus dem Dataset abzurufenden Felder.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-113">Gets or sets fields of metadata to get from dataset.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GetMetadataActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="getMetadataActivity.Validate " />
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
            <span data-ttu-id="dd0ad-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dd0ad-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd0ad-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dd0ad-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>