<Type Name="VirtualMachineExtensionImage" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage">
  <TypeSignature Language="C#" Value="public class VirtualMachineExtensionImage : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineExtensionImage extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineExtensionImage&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionImage = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibt die Abbild eines virtuellen Computers-Erweiterung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtensionImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.#ctor" />
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
            Initialisiert eine neue Instanz der VirtualMachineExtensionImage-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtensionImage (string location, string operatingSystem, string computeRole, string handlerSchema, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;bool&gt; vmScaleSetEnabled = null, Nullable&lt;bool&gt; supportsMultipleExtensions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string operatingSystem, string computeRole, string handlerSchema, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; vmScaleSetEnabled, valuetype System.Nullable`1&lt;bool&gt; supportsMultipleExtensions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, operatingSystem As String, computeRole As String, handlerSchema As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional vmScaleSetEnabled As Nullable(Of Boolean) = null, Optional supportsMultipleExtensions As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage : string * string * string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage (location, operatingSystem, computeRole, handlerSchema, id, name, type, tags, vmScaleSetEnabled, supportsMultipleExtensions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="operatingSystem" Type="System.String" />
        <Parameter Name="computeRole" Type="System.String" />
        <Parameter Name="handlerSchema" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="vmScaleSetEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="supportsMultipleExtensions" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="location">Speicherort von Ressourcen</param>
        <param name="operatingSystem">Das Betriebssystem, das diese Erweiterung unterstützt.</param>
        <param name="computeRole">Der Typ der Rolle (IaaS oder PaaS) unterstützt diese Erweiterung.</param>
        <param name="handlerSchema">Das Schema definiert, die vom Herausgeber, wobei Erweiterung Consumer Einstellungen in ein übereinstimmendes Schema bereitstellen soll.</param>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="tags">Ressourcentags</param>
        <param name="vmScaleSetEnabled">Gibt an, ob die Erweiterung auf xRP VMScaleSets verwendet werden kann. Standardmäßig vorhandene Erweiterungen für Scalesets verwendet werden, aber es gibt möglicherweise Fälle, in dem ein Verleger möchte, um explizit anzugeben, dass die Erweiterung nur für CRP-VMs, aber nicht VMSS aktiviert ist.</param>
        <param name="supportsMultipleExtensions">Gibt an, ob der Handler für mehrere Erweiterungen unterstützen kann.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineExtensionImage-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeRole">
      <MemberSignature Language="C#" Value="public string ComputeRole { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputeRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.ComputeRole" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputeRole As String" />
      <MemberSignature Language="F#" Value="member this.ComputeRole : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.ComputeRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.computeRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt dem Typ der Rolle (IaaS oder PaaS) diese Erweiterung unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandlerSchema">
      <MemberSignature Language="C#" Value="public string HandlerSchema { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HandlerSchema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.HandlerSchema" />
      <MemberSignature Language="VB.NET" Value="Public Property HandlerSchema As String" />
      <MemberSignature Language="F#" Value="member this.HandlerSchema : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.HandlerSchema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.handlerSchema")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert das Schema definiert, die vom Herausgeber, Erweiterung Consumer sollte, in denen Einstellungen in ein übereinstimmendes Schema bereitstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatingSystem">
      <MemberSignature Language="C#" Value="public string OperatingSystem { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperatingSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.OperatingSystem" />
      <MemberSignature Language="VB.NET" Value="Public Property OperatingSystem As String" />
      <MemberSignature Language="F#" Value="member this.OperatingSystem : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.OperatingSystem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operatingSystem")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Betriebssystem, das diese Erweiterung unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsMultipleExtensions">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SupportsMultipleExtensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SupportsMultipleExtensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.SupportsMultipleExtensions" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportsMultipleExtensions As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SupportsMultipleExtensions : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.SupportsMultipleExtensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportsMultipleExtensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Ereignishandler mehrere Erweiterungen unterstützen kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualMachineExtensionImage.Validate " />
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmScaleSetEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; VmScaleSetEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; VmScaleSetEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.VmScaleSetEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property VmScaleSetEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.VmScaleSetEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage.VmScaleSetEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmScaleSetEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Erweiterung für xRP VMScaleSets verwendet werden kann.
            Standardmäßig vorhandene Erweiterungen für Scalesets verwendet werden, aber es gibt möglicherweise Fälle, in dem ein Verleger möchte, um explizit anzugeben, dass die Erweiterung nur für CRP-VMs, aber nicht VMSS aktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>