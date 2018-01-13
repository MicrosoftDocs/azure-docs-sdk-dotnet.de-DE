<Type Name="PolybaseSettings" FullName="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings">
  <TypeSignature Language="C#" Value="public class PolybaseSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolybaseSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class PolybaseSettings" />
  <TypeSignature Language="F#" Value="type PolybaseSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f3e4b-101">PolyBase-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-101">PolyBase settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolybaseSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.#ctor" />
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
            <span data-ttu-id="f3e4b-102">Initialisiert eine neue Instanz der PolybaseSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-102">Initializes a new instance of the PolybaseSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolybaseSettings (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string rejectType = null, object rejectValue = null, object rejectSampleValue = null, object useTypeDefault = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string rejectType, object rejectValue, object rejectSampleValue, object useTypeDefault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional rejectType As String = null, Optional rejectValue As Object = null, Optional rejectSampleValue As Object = null, Optional useTypeDefault As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings" Usage="new Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings (additionalProperties, rejectType, rejectValue, rejectSampleValue, useTypeDefault)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="rejectType" Type="System.String" />
        <Parameter Name="rejectValue" Type="System.Object" />
        <Parameter Name="rejectSampleValue" Type="System.Object" />
        <Parameter Name="useTypeDefault" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="f3e4b-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="f3e4b-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="rejectType"><span data-ttu-id="f3e4b-104">Lehnen Sie Typ an ab.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-104">Reject type.</span></span> <span data-ttu-id="f3e4b-105">Folgende Werte sind möglich: "value", "Percentage"</span><span class="sxs-lookup"><span data-stu-id="f3e4b-105">Possible values include: 'value', 'percentage'</span></span></param>
        <param name="rejectValue"><span data-ttu-id="f3e4b-106">Gibt den Wert oder den Prozentsatz der Zeilen, die zurückgewiesen werden kann, bevor die Abfrage fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-106">Specifies the value or the percentage of rows that can be rejected before the query fails.</span></span> <span data-ttu-id="f3e4b-107">Typ: Nummer (oder Ausdruck mit ResultType-Anzahl), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-107">Type: number (or Expression with resultType number), minimum: 0.</span></span></param>
        <param name="rejectSampleValue"><span data-ttu-id="f3e4b-108">Bestimmt die Anzahl der Zeilen abrufen, bevor die PolyBase berechnet den Prozentsatz der abgelehnten Zeilen neu versucht.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-108">Determines the number of rows to attempt to retrieve before the PolyBase recalculates the percentage of rejected rows.</span></span> <span data-ttu-id="f3e4b-109">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-109">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="useTypeDefault"><span data-ttu-id="f3e4b-110">Gibt an, wie fehlende Werte in durch Trennzeichen getrennten Textdateien verarbeitet werden sollen, wenn PolyBase Daten aus der Textdatei abruft.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-110">Specifies how to handle missing values in delimited text files when PolyBase retrieves data from the text file.</span></span> <span data-ttu-id="f3e4b-111">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="f3e4b-111">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="f3e4b-112">Initialisiert eine neue Instanz der PolybaseSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-112">Initializes a new instance of the PolybaseSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3e4b-113">Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="f3e4b-113">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectSampleValue">
      <MemberSignature Language="C#" Value="public object RejectSampleValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RejectSampleValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectSampleValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectSampleValue As Object" />
      <MemberSignature Language="F#" Value="member this.RejectSampleValue : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectSampleValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rejectSampleValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3e4b-114">Ruft ab oder legt bestimmt die Anzahl der Zeilen abrufen, bevor die PolyBase berechnet den Prozentsatz der abgelehnten Zeilen neu versucht.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-114">Gets or sets determines the number of rows to attempt to retrieve before the PolyBase recalculates the percentage of rejected rows.</span></span>
            <span data-ttu-id="f3e4b-115">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-115">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectType">
      <MemberSignature Language="C#" Value="public string RejectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RejectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectType" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectType As String" />
      <MemberSignature Language="F#" Value="member this.RejectType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rejectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3e4b-116">Lehnen Typ, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-116">Gets or sets reject type.</span></span> <span data-ttu-id="f3e4b-117">Folgende Werte sind möglich: "value", "Percentage"</span><span class="sxs-lookup"><span data-stu-id="f3e4b-117">Possible values include: 'value', 'percentage'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectValue">
      <MemberSignature Language="C#" Value="public object RejectValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RejectValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectValue As Object" />
      <MemberSignature Language="F#" Value="member this.RejectValue : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rejectValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3e4b-118">Ruft ab oder legt gibt den Wert oder den Prozentsatz der Zeilen, die zurückgewiesen werden kann, bevor die Abfrage fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-118">Gets or sets specifies the value or the percentage of rows that can be rejected before the query fails.</span></span> <span data-ttu-id="f3e4b-119">Typ: Nummer (oder Ausdruck mit ResultType-Anzahl), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-119">Type: number (or Expression with resultType number), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTypeDefault">
      <MemberSignature Language="C#" Value="public object UseTypeDefault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseTypeDefault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.UseTypeDefault" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTypeDefault As Object" />
      <MemberSignature Language="F#" Value="member this.UseTypeDefault : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.UseTypeDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="useTypeDefault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3e4b-120">Gibt an, wie fehlende Werte in einer durch Trennzeichen getrennten Textdateien behandelt wird, wenn PolyBase Daten aus der Textdatei abruft Ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="f3e4b-120">Gets or sets specifies how to handle missing values in delimited text files when PolyBase retrieves data from the text file.</span></span> <span data-ttu-id="f3e4b-121">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="f3e4b-121">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>