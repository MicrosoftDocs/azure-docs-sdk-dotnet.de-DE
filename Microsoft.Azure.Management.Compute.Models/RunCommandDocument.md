<Type Name="RunCommandDocument" FullName="Microsoft.Azure.Management.Compute.Models.RunCommandDocument">
  <TypeSignature Language="C#" Value="public class RunCommandDocument : Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RunCommandDocument extends Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RunCommandDocument" />
  <TypeSignature Language="VB.NET" Value="Public Class RunCommandDocument&#xA;Inherits RunCommandDocumentBase" />
  <TypeSignature Language="F#" Value="type RunCommandDocument = class&#xA;    inherit RunCommandDocumentBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="28984-101">Beschreibt die Eigenschaften eines Befehls ausführen.</span><span class="sxs-lookup"><span data-stu-id="28984-101">Describes the properties of a Run Command.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandDocument ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandDocument.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="28984-102">Initialisiert eine neue Instanz der RunCommandDocument-Klasse.</span><span class="sxs-lookup"><span data-stu-id="28984-102">Initializes a new instance of the RunCommandDocument class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandDocument (string schema, string id, Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes osType, string label, string description, System.Collections.Generic.IList&lt;string&gt; script, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string schema, string id, valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes osType, string label, string description, class System.Collections.Generic.IList`1&lt;string&gt; script, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandDocument.#ctor(System.String,System.String,Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (schema As String, id As String, osType As OperatingSystemTypes, label As String, description As String, script As IList(Of String), Optional parameters As IList(Of RunCommandParameterDefinition) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RunCommandDocument : string * string * Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition&gt; -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandDocument" Usage="new Microsoft.Azure.Management.Compute.Models.RunCommandDocument (schema, id, osType, label, description, script, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schema" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes" />
        <Parameter Name="label" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="script" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition&gt;" />
      </Parameters>
      <Docs>
        <param name="schema"><span data-ttu-id="28984-103">Das Schema für den virtuellen Computer ausführen-Befehl.</span><span class="sxs-lookup"><span data-stu-id="28984-103">The VM run command schema.</span></span></param>
        <param name="id"><span data-ttu-id="28984-104">Die Befehls-Id des virtuellen Computers ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="28984-104">The VM run command id.</span></span></param>
        <param name="osType"><span data-ttu-id="28984-105">Der Typ des Betriebssystems.</span><span class="sxs-lookup"><span data-stu-id="28984-105">The Operating System type.</span></span> <span data-ttu-id="28984-106">Folgende Werte sind möglich: "Windows", "Linux"</span><span class="sxs-lookup"><span data-stu-id="28984-106">Possible values include: 'Windows', 'Linux'</span></span></param>
        <param name="label"><span data-ttu-id="28984-107">Die Bezeichnung für den virtuellen Computer ausführen-Befehl.</span><span class="sxs-lookup"><span data-stu-id="28984-107">The VM run command label.</span></span></param>
        <param name="description"><span data-ttu-id="28984-108">Der virtuelle Computer, die Beschreibung der Befehl ausführen.</span><span class="sxs-lookup"><span data-stu-id="28984-108">The VM run command description.</span></span></param>
        <param name="script"><span data-ttu-id="28984-109">Das Skript ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="28984-109">The script to be executed.</span></span></param>
        <param name="parameters"><span data-ttu-id="28984-110">Die Parameter, die vom Skript verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="28984-110">The parameters used by the script.</span></span></param>
        <summary>
            <span data-ttu-id="28984-111">Initialisiert eine neue Instanz der RunCommandDocument-Klasse.</span><span class="sxs-lookup"><span data-stu-id="28984-111">Initializes a new instance of the RunCommandDocument class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandDocument.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IList(Of RunCommandParameterDefinition)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandDocument.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28984-112">Ruft ab oder legt die Parameter, die vom Skript verwendet.</span><span class="sxs-lookup"><span data-stu-id="28984-112">Gets or sets the parameters used by the script.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandDocument.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Script : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandDocument.Script" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="script")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28984-113">Ruft ab oder legt das Skript ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="28984-113">Gets or sets the script to be executed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandDocument.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="runCommandDocument.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="28984-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="28984-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28984-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="28984-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>