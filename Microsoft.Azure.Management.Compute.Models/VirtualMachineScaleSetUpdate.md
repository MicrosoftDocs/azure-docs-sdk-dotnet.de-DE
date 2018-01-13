<Type Name="VirtualMachineScaleSetUpdate" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetUpdate : Microsoft.Azure.Management.Compute.Models.UpdateResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetUpdate extends Microsoft.Azure.Management.Compute.Models.UpdateResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetUpdate&#xA;Inherits UpdateResource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetUpdate = class&#xA;    inherit UpdateResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.UpdateResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibt eine VM-Skalierungsgruppe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetUpdate-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdate (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Models.Sku sku = null, Microsoft.Azure.Management.Compute.Models.Plan plan = null, Microsoft.Azure.Management.Compute.Models.UpgradePolicy upgradePolicy = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile virtualMachineProfile = null, Nullable&lt;bool&gt; overprovision = null, Nullable&lt;bool&gt; singlePlacementGroup = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity identity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Models.Sku sku, class Microsoft.Azure.Management.Compute.Models.Plan plan, class Microsoft.Azure.Management.Compute.Models.UpgradePolicy upgradePolicy, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile virtualMachineProfile, valuetype System.Nullable`1&lt;bool&gt; overprovision, valuetype System.Nullable`1&lt;bool&gt; singlePlacementGroup, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Models.Sku,Microsoft.Azure.Management.Compute.Models.Plan,Microsoft.Azure.Management.Compute.Models.UpgradePolicy,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Models.Sku * Microsoft.Azure.Management.Compute.Models.Plan * Microsoft.Azure.Management.Compute.Models.UpgradePolicy * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate (tags, sku, plan, upgradePolicy, virtualMachineProfile, overprovision, singlePlacementGroup, identity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Models.Sku" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Models.Plan" />
        <Parameter Name="upgradePolicy" Type="Microsoft.Azure.Management.Compute.Models.UpgradePolicy" />
        <Parameter Name="virtualMachineProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile" />
        <Parameter Name="overprovision" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="singlePlacementGroup" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity" />
      </Parameters>
      <Docs>
        <param name="tags">Ressourcentags</param>
        <param name="sku">Die VM-Skalierungsgruppe Sku.</param>
        <param name="plan">Des erwerbsplans, wenn eine VM-Skalierungsgruppe Bereitstellen von VM-Marketplace-Images festgelegt.</param>
        <param name="upgradePolicy">Die Upgraderichtlinie.</param>
        <param name="virtualMachineProfile">Das Profil des virtuellen Computers.</param>
        <param name="overprovision">Gibt an, ob die VM-Skalierungsgruppe overprovisioned werden sollte.</param>
        <param name="singlePlacementGroup">Bei "true" schränkt dies die Skalierung auf ein einzelnes Platzierung Gruppe, Max. 100 virtueller Maschinen festgelegt.</param>
        <param name="identity">Die Identität des VM-Skalierungsgruppe, wenn konfiguriert.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetUpdate-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As VirtualMachineScaleSetIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Identität des VM-Skalierungsgruppe, sofern konfiguriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overprovision">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overprovision { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overprovision" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Overprovision" />
      <MemberSignature Language="VB.NET" Value="Public Property Overprovision As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overprovision : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Overprovision" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overprovision")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest gibt an, ob die VM-Skalierungsgruppe overprovisioned werden sollte.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Models.Plan with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="plan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Plan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des erwerbsplans aus, wenn eine VM-Skalierungsgruppe Bereitstellen von VM-Marketplace-Images festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SinglePlacementGroup">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SinglePlacementGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SinglePlacementGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.SinglePlacementGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property SinglePlacementGroup As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SinglePlacementGroup : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.SinglePlacementGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.singlePlacementGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, bei "true", damit das Scale set zu einer einzelnen Platzierung-Gruppe, der maximalen Größe 100 virtuelle Computer ist eingeschränkt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die virtuellen Maschine Skalierung Set-Sku.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.UpgradePolicy UpgradePolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.UpgradePolicy UpgradePolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.UpgradePolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradePolicy As UpgradePolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradePolicy : Microsoft.Azure.Management.Compute.Models.UpgradePolicy with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.UpgradePolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradePolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.UpgradePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Upgraderichtlinie.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetUpdate.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
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
    <Member MemberName="VirtualMachineProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile VirtualMachineProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile VirtualMachineProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.VirtualMachineProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineProfile As VirtualMachineScaleSetUpdateVMProfile" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.VirtualMachineProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Profil des virtuellen Computers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>