<Type Name="ContainerGroup" FullName="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup">
  <TypeSignature Language="C#" Value="public class ContainerGroup : Microsoft.Azure.Management.ContainerInstance.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerGroup extends Microsoft.Azure.Management.ContainerInstance.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerGroup&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ContainerGroup = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ContainerInstance.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Ein Containergruppe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ContainerGroup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerGroup (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string provisioningState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; containers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; imageRegistryCredentials = null, string restartPolicy = null, Microsoft.Azure.Management.ContainerInstance.Models.IpAddress ipAddress = null, string osType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; volumes = null, Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView instanceView = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string provisioningState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; containers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; imageRegistryCredentials, string restartPolicy, class Microsoft.Azure.Management.ContainerInstance.Models.IpAddress ipAddress, string osType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; volumes, class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView instanceView) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.Container},System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential},System.String,Microsoft.Azure.Management.ContainerInstance.Models.IpAddress,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.Volume},Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; * string * Microsoft.Azure.Management.ContainerInstance.Models.IpAddress * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; * Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup (location, id, name, type, tags, provisioningState, containers, imageRegistryCredentials, restartPolicy, ipAddress, osType, volumes, instanceView)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="containers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt;" />
        <Parameter Name="imageRegistryCredentials" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt;" />
        <Parameter Name="restartPolicy" Type="System.String" />
        <Parameter Name="ipAddress" Type="Microsoft.Azure.Management.ContainerInstance.Models.IpAddress" />
        <Parameter Name="osType" Type="System.String" />
        <Parameter Name="volumes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt;" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView" />
      </Parameters>
      <Docs>
        <param name="location">Der Ressourcenspeicherort.</param>
        <param name="id">Die Ressourcen-Id.</param>
        <param name="name">Der Ressourcenname.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="tags">Der Ressourcen-Tags.</param>
        <param name="provisioningState">Der Bereitstellungsstatus der Gruppe "Container". Dies wird nur in der Antwort angezeigt.</param>
        <param name="containers">Der Container innerhalb der Containergruppe.</param>
        <param name="imageRegistryCredentials">Die Anmeldeinformationen des Image-Registrierung, die durch denen die Containergruppe erstellt wurde, aus.</param>
        <param name="restartPolicy">Starten Sie die Richtlinie für alle Container innerhalb der Containergruppe neu.
            - `Always`Immer neu gestartet
            - `OnFailure`Fehler beim erneuten Starten
            - `Never`Nie neu starten. Folgende Werte sind möglich: "Immer", "OnFailure", "Nie"</param>
        <param name="ipAddress">Die IP-Adresstyp der Gruppe "Container".</param>
        <param name="osType">Der Typ des Betriebssystems, die Container in der Containergruppe erforderlich. Folgende Werte sind möglich: "Windows", "Linux"</param>
        <param name="volumes">Die Liste der Volumes, die von Containern in dieser Containergruppe eingebunden werden können.</param>
        <param name="instanceView">Die Instanzansicht der Gruppe "Container". In der Antwort nur gültig.</param>
        <summary>
            Initialisiert eine neue Instanz der ContainerGroup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Containers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; Containers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; Containers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Containers" />
      <MemberSignature Language="VB.NET" Value="Public Property Containers As IList(Of Container)" />
      <MemberSignature Language="F#" Value="member this.Containers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Containers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Container innerhalb der Containergruppe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageRegistryCredentials">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; ImageRegistryCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; ImageRegistryCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.ImageRegistryCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageRegistryCredentials As IList(Of ImageRegistryCredential)" />
      <MemberSignature Language="F#" Value="member this.ImageRegistryCredentials : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.ImageRegistryCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.imageRegistryCredentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Bild Registrierung Anmeldeinformationen, die Containergruppe erstellt wurde, aus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As ContainerGroupPropertiesInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceView")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Instanzansicht der Gruppe "Container" ab. In der Antwort nur gültig.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.IpAddress IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.IpAddress IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As IpAddress" />
      <MemberSignature Language="F#" Value="member this.IpAddress : Microsoft.Azure.Management.ContainerInstance.Models.IpAddress with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.IpAddress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die IP-Adresstyp, der Gruppe "Container".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public string OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As String" />
      <MemberSignature Language="F#" Value="member this.OsType : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des Betriebssystems, die Container in der Containergruppe erforderlich. Folgende Werte sind möglich: "Windows", "Linux"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bereitstellungsstatus der Gruppe "Container" ab. Dies wird nur in der Antwort angezeigt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartPolicy">
      <MemberSignature Language="C#" Value="public string RestartPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RestartPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.RestartPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RestartPolicy As String" />
      <MemberSignature Language="F#" Value="member this.RestartPolicy : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.RestartPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.restartPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt neu starten-Richtlinie für alle Container innerhalb der Containergruppe aus.
            - `Always`Immer neu gestartet
            - `OnFailure`Fehler beim erneuten Starten
            - `Never`Nie neu starten. Folgende Werte sind möglich: "Immer", "OnFailure", "Nie"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="containerGroup.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
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
    <Member MemberName="Volumes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; Volumes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; Volumes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Volumes" />
      <MemberSignature Language="VB.NET" Value="Public Property Volumes As IList(Of Volume)" />
      <MemberSignature Language="F#" Value="member this.Volumes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Volumes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Volumes, die von Containern in dieser Containergruppe eingebunden werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>