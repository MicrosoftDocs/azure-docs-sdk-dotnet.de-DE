<Type Name="VnetValidationFailureDetails" FullName="Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails">
  <TypeSignature Language="C#" Value="public class VnetValidationFailureDetails : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetValidationFailureDetails extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetValidationFailureDetails&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetValidationFailureDetails = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="893f2-101">Eine Klasse, die den Grund für einen Validierungsfehler beschreibt.</span><span class="sxs-lookup"><span data-stu-id="893f2-101">A class that describes the reason for a validation failure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetValidationFailureDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="893f2-102">Initialisiert eine neue Instanz der VnetValidationFailureDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="893f2-102">Initializes a new instance of the VnetValidationFailureDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetValidationFailureDetails (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;bool&gt; failed = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure&gt; failedTests = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;bool&gt; failed, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure&gt; failedTests) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional failed As Nullable(Of Boolean) = null, Optional failedTests As IList(Of VnetValidationTestFailure) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails : string * string * string * string * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails" Usage="new Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails (id, name, kind, type, failed, failedTests)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="failed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="failedTests" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="893f2-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="893f2-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="893f2-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="893f2-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="893f2-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="893f2-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="893f2-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="893f2-106">Resource type.</span></span></param>
        <param name="failed"><span data-ttu-id="893f2-107">Ein Flag, ob Fehler bei der Überprüfung beschreibt.</span><span class="sxs-lookup"><span data-stu-id="893f2-107">A flag describing whether or not validation failed.</span></span></param>
        <param name="failedTests"><span data-ttu-id="893f2-108">Eine Liste der Tests, die in die Überprüfung nicht bestanden.</span><span class="sxs-lookup"><span data-stu-id="893f2-108">A list of tests that failed in the validation.</span></span></param>
        <summary>
            <span data-ttu-id="893f2-109">Initialisiert eine neue Instanz der VnetValidationFailureDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="893f2-109">Initializes a new instance of the VnetValidationFailureDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Failed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Failed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails.Failed" />
      <MemberSignature Language="VB.NET" Value="Public Property Failed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Failed : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails.Failed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.failed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="893f2-110">Ruft ab oder legt ein Flag, ob Fehler bei der Überprüfung beschreibt.</span><span class="sxs-lookup"><span data-stu-id="893f2-110">Gets or sets a flag describing whether or not validation failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedTests">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure&gt; FailedTests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure&gt; FailedTests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails.FailedTests" />
      <MemberSignature Language="VB.NET" Value="Public Property FailedTests As IList(Of VnetValidationTestFailure)" />
      <MemberSignature Language="F#" Value="member this.FailedTests : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails.FailedTests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.failedTests")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="893f2-111">Ruft ab oder legt eine Liste der fehlgeschlagenen Tests in die Überprüfung.</span><span class="sxs-lookup"><span data-stu-id="893f2-111">Gets or sets a list of tests that failed in the validation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>