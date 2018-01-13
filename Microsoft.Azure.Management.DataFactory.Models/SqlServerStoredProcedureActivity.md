<Type Name="SqlServerStoredProcedureActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity">
  <TypeSignature Language="C#" Value="public class SqlServerStoredProcedureActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlServerStoredProcedureActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlServerStoredProcedureActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type SqlServerStoredProcedureActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("SqlServerStoredProcedure")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="562a7-101">Gespeicherte SQL-Prozedur Aktivitätstyp.</span><span class="sxs-lookup"><span data-stu-id="562a7-101">SQL stored procedure activity type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlServerStoredProcedureActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity.#ctor" />
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
            <span data-ttu-id="562a7-102">Initialisiert eine neue Instanz der SqlServerStoredProcedureActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="562a7-102">Initializes a new instance of the SqlServerStoredProcedureActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlServerStoredProcedureActivity (string name, object storedProcedureName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; storedProcedureParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object storedProcedureName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; storedProcedureParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity.#ctor(System.String,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, storedProcedureName As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional storedProcedureParameters As IDictionary(Of String, StoredProcedureParameter) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity : string * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity (name, storedProcedureName, additionalProperties, description, dependsOn, linkedServiceName, policy, storedProcedureParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storedProcedureName" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="storedProcedureParameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="562a7-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="562a7-103">Activity name.</span></span></param>
        <param name="storedProcedureName"><span data-ttu-id="562a7-104">Name der gespeicherten Prozedur.</span><span class="sxs-lookup"><span data-stu-id="562a7-104">Stored procedure name.</span></span> <span data-ttu-id="562a7-105">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="562a7-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="562a7-106">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="562a7-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="562a7-107">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="562a7-107">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="562a7-108">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="562a7-108">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="562a7-109">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="562a7-109">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="562a7-110">"Aktivitätsrichtlinie".</span><span class="sxs-lookup"><span data-stu-id="562a7-110">Activity policy.</span></span></param>
        <param name="storedProcedureParameters"><span data-ttu-id="562a7-111">Wert und Typ für Parameter gespeicherter Prozeduren festlegen.</span><span class="sxs-lookup"><span data-stu-id="562a7-111">Value and type setting for stored procedure parameters.</span></span> <span data-ttu-id="562a7-112">Beispiel: "{Parameter1: {Wert:"1", Typ:"Int"}}".</span><span class="sxs-lookup"><span data-stu-id="562a7-112">Example: "{Parameter1: {value: "1", type: "int"}}".</span></span></param>
        <summary>
            <span data-ttu-id="562a7-113">Initialisiert eine neue Instanz der SqlServerStoredProcedureActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="562a7-113">Initializes a new instance of the SqlServerStoredProcedureActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureName">
      <MemberSignature Language="C#" Value="public object StoredProcedureName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object StoredProcedureName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity.StoredProcedureName" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureName As Object" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity.StoredProcedureName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.storedProcedureName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="562a7-114">Ruft ab oder legt Name der gespeicherten Prozedur.</span><span class="sxs-lookup"><span data-stu-id="562a7-114">Gets or sets stored procedure name.</span></span> <span data-ttu-id="562a7-115">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="562a7-115">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; StoredProcedureParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; StoredProcedureParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity.StoredProcedureParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureParameters As IDictionary(Of String, StoredProcedureParameter)" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureParameters : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity.StoredProcedureParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.storedProcedureParameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="562a7-116">Ruft ab, oder legt sie fest, Wert und Typ für Parameter gespeicherter Prozeduren festlegen.</span><span class="sxs-lookup"><span data-stu-id="562a7-116">Gets or sets value and type setting for stored procedure parameters.</span></span> <span data-ttu-id="562a7-117">Beispiel: "{Parameter1: {Wert:"1", Typ:"Int"}}".</span><span class="sxs-lookup"><span data-stu-id="562a7-117">Example: "{Parameter1: {value: "1", type: "int"}}".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlServerStoredProcedureActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sqlServerStoredProcedureActivity.Validate " />
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
            <span data-ttu-id="562a7-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="562a7-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="562a7-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="562a7-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>