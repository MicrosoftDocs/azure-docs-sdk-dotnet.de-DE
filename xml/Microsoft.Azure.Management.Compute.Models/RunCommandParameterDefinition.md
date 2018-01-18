<Type Name="RunCommandParameterDefinition" FullName="Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition">
  <TypeSignature Language="C#" Value="public class RunCommandParameterDefinition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RunCommandParameterDefinition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class RunCommandParameterDefinition" />
  <TypeSignature Language="F#" Value="type RunCommandParameterDefinition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8c3eb-101">Beschreibt die Eigenschaften eines Ausführungsbefehls-Parameters.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-101">Describes the properties of a run command parameter.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandParameterDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.#ctor" />
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
            <span data-ttu-id="8c3eb-102">Initialisiert eine neue Instanz der RunCommandParameterDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-102">Initializes a new instance of the RunCommandParameterDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandParameterDefinition (string name, string type, string defaultValue = null, Nullable&lt;bool&gt; required = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string type, string defaultValue, valuetype System.Nullable`1&lt;bool&gt; required) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.#ctor(System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, type As String, Optional defaultValue As String = null, Optional required As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition : string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition" Usage="new Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition (name, type, defaultValue, required)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="defaultValue" Type="System.String" />
        <Parameter Name="required" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8c3eb-103">Der Name des ausgeführten Befehls-Parameters.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-103">The run command parameter name.</span></span></param>
        <param name="type"><span data-ttu-id="8c3eb-104">Der Typ des ausgeführten Befehls-Parameter.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-104">The run command parameter type.</span></span></param>
        <param name="defaultValue"><span data-ttu-id="8c3eb-105">Der Standardwert für den ausgeführten Befehls Parameter.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-105">The run command parameter default value.</span></span></param>
        <param name="required"><span data-ttu-id="8c3eb-106">Der Ausführungsbefehls-Parameter erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-106">The run command parameter required.</span></span></param>
        <summary>
            <span data-ttu-id="8c3eb-107">Initialisiert eine neue Instanz der RunCommandParameterDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-107">Initializes a new instance of the RunCommandParameterDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultValue">
      <MemberSignature Language="C#" Value="public string DefaultValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.DefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultValue As String" />
      <MemberSignature Language="F#" Value="member this.DefaultValue : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.DefaultValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c3eb-108">Ruft ab oder legt den Standardwert des ausgeführten Befehls Parameter fest.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-108">Gets or sets the run command parameter default value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c3eb-109">Ruft ab, oder legt ihn fest der Name des ausgeführten Befehls-Parameters.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-109">Gets or sets the run command parameter name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Required">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Required { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Required" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.Required" />
      <MemberSignature Language="VB.NET" Value="Public Property Required As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Required : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.Required" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="required")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c3eb-110">Abrufen oder festlegen den ausgeführten Befehlsparameter erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-110">Gets or sets the run command parameter required.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c3eb-111">Ruft ab oder legt den Typ des ausgeführten Befehls Parameter fest.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-111">Gets or sets the run command parameter type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandParameterDefinition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="runCommandParameterDefinition.Validate " />
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
            <span data-ttu-id="8c3eb-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="8c3eb-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8c3eb-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="8c3eb-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>