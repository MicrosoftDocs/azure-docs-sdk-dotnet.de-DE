<Type Name="VirtualNetworkRule" FullName="Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule">
  <TypeSignature Language="C#" Value="public class VirtualNetworkRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkRule" />
  <TypeSignature Language="F#" Value="type VirtualNetworkRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Virtuelle Netzwerkregel.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualNetworkRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkRule (string virtualNetworkResourceId, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt; action = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.State&gt; state = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string virtualNetworkResourceId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Action&gt; action, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.State&gt; state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.Action},System.Nullable{Microsoft.Azure.Management.Storage.Models.State})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (virtualNetworkResourceId As String, Optional action As Nullable(Of Action) = null, Optional state As Nullable(Of State) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule : string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt; * Nullable&lt;Microsoft.Azure.Management.Storage.Models.State&gt; -&gt; Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule" Usage="new Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule (virtualNetworkResourceId, action, state)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="virtualNetworkResourceId" Type="System.String" />
        <Parameter Name="action" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.State&gt;" />
      </Parameters>
      <Docs>
        <param name="virtualNetworkResourceId">Ressourcen-ID eines Subnetzes, z. B.: /subscriptions/{subscriptionId}/resourceGroups/{groupName}/providers/Microsoft.Network/virtualNetworks/{vnetName}/subnets/{subnetName}.</param>
        <param name="action">Die Aktion der virtuellen Netzwerkregel. Folgende Werte sind möglich: "Zulassen"</param>
        <param name="state">Ruft den Zustand der virtuellen Netzwerkregel ab.
            Folgende Werte sind möglich: "Bereitstellung", "Aufheben der Bereitstellung", "erfolgreich abgeschlossen", "fehlgeschlagen", "NetworkSourceDeleted"</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualNetworkRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt; Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Action&gt; Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As Nullable(Of Action)" />
      <MemberSignature Language="F#" Value="member this.Action : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Aktion der virtuellen Netzwerkregel. Folgende Werte sind möglich: "Zulassen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.State&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.State&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of State)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.Storage.Models.State&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.State&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zustand der virtuellen Netzwerkregel ab. Folgende Werte sind möglich: "Bereitstellung", "Aufheben der Bereitstellung", "erfolgreich abgeschlossen", "fehlgeschlagen", "NetworkSourceDeleted"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualNetworkRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
    <Member MemberName="VirtualNetworkResourceId">
      <MemberSignature Language="C#" Value="public string VirtualNetworkResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualNetworkResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule.VirtualNetworkResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkResourceId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkResourceId : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule.VirtualNetworkResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Sie die Ressourcen-ID eines Subnetzes, z. B.: /subscriptions/{subscriptionId}/resourceGroups/{groupName}/providers/Microsoft.Network/virtualNetworks/{vnetName}/subnets/{subnetName}.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>