<Type Name="RunCommandInput" FullName="Microsoft.Azure.Management.Compute.Models.RunCommandInput">
  <TypeSignature Language="C#" Value="public class RunCommandInput" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RunCommandInput extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
  <TypeSignature Language="VB.NET" Value="Public Class RunCommandInput" />
  <TypeSignature Language="F#" Value="type RunCommandInput = class" />
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
            <span data-ttu-id="a3215-101">Parameter des virtuellen Computers zu erfassen.</span><span class="sxs-lookup"><span data-stu-id="a3215-101">Capture Virtual Machine parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandInput ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandInput.#ctor" />
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
            <span data-ttu-id="a3215-102">Initialisiert eine neue Instanz der RunCommandInput-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a3215-102">Initializes a new instance of the RunCommandInput class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandInput (string commandId, System.Collections.Generic.IList&lt;string&gt; script = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandInputParameter&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandId, class System.Collections.Generic.IList`1&lt;string&gt; script, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandInputParameter&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandInput.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.RunCommandInputParameter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (commandId As String, Optional script As IList(Of String) = null, Optional parameters As IList(Of RunCommandInputParameter) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RunCommandInput : string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandInputParameter&gt; -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandInput" Usage="new Microsoft.Azure.Management.Compute.Models.RunCommandInput (commandId, script, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandId" Type="System.String" />
        <Parameter Name="script" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandInputParameter&gt;" />
      </Parameters>
      <Docs>
        <param name="commandId"><span data-ttu-id="a3215-103">Die Id des ausgeführten Befehls.</span><span class="sxs-lookup"><span data-stu-id="a3215-103">The run command id.</span></span></param>
        <param name="script"><span data-ttu-id="a3215-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="a3215-104">Optional.</span></span> <span data-ttu-id="a3215-105">Das Skript ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a3215-105">The script to be executed.</span></span>  <span data-ttu-id="a3215-106">Wenn dieser Wert angegeben ist, werden das angegebene Skript das Standardskript des Befehls überschrieben.</span><span class="sxs-lookup"><span data-stu-id="a3215-106">When this value is given, the given script will override the default script of the command.</span></span></param>
        <param name="parameters"><span data-ttu-id="a3215-107">Die Parameter des Befehls ausführen.</span><span class="sxs-lookup"><span data-stu-id="a3215-107">The run command parameters.</span></span></param>
        <summary>
            <span data-ttu-id="a3215-108">Initialisiert eine neue Instanz der RunCommandInput-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a3215-108">Initializes a new instance of the RunCommandInput class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandId">
      <MemberSignature Language="C#" Value="public string CommandId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandInput.CommandId" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandId As String" />
      <MemberSignature Language="F#" Value="member this.CommandId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandInput.CommandId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3215-109">Ruft ab oder legt die Id des ausgeführten Befehls fest.</span><span class="sxs-lookup"><span data-stu-id="a3215-109">Gets or sets the run command id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandInputParameter&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandInputParameter&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandInput.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IList(Of RunCommandInputParameter)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandInputParameter&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandInput.Parameters" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.RunCommandInputParameter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3215-110">Ermittelt oder definiert die Parameter des Befehls ausführen.</span><span class="sxs-lookup"><span data-stu-id="a3215-110">Gets or sets the run command parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandInput.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Script : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandInput.Script" />
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
            <span data-ttu-id="a3215-111">Ruft ab oder legt dies ist optional.</span><span class="sxs-lookup"><span data-stu-id="a3215-111">Gets or sets optional.</span></span> <span data-ttu-id="a3215-112">Das Skript ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a3215-112">The script to be executed.</span></span>  <span data-ttu-id="a3215-113">Wenn dieser Wert angegeben ist, werden das angegebene Skript das Standardskript des Befehls überschrieben.</span><span class="sxs-lookup"><span data-stu-id="a3215-113">When this value is given, the given script will override the default script of the command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandInput.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="runCommandInput.Validate " />
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
            <span data-ttu-id="a3215-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a3215-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a3215-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a3215-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>