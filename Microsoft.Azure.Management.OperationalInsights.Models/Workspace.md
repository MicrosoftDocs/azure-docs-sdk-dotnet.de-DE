<Type Name="Workspace" FullName="Microsoft.Azure.Management.OperationalInsights.Models.Workspace">
  <TypeSignature Language="C#" Value="public class Workspace : Microsoft.Azure.Management.OperationalInsights.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Workspace extends Microsoft.Azure.Management.OperationalInsights.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
  <TypeSignature Language="VB.NET" Value="Public Class Workspace&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Workspace = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.OperationalInsights.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die oberste Ebene Arbeitsbereich Ressource Container.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Workspace ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Arbeitsbereich.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Workspace (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string provisioningState = null, string source = null, string customerId = null, string portalUrl = null, Microsoft.Azure.Management.OperationalInsights.Models.Sku sku = null, Nullable&lt;int&gt; retentionInDays = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string provisioningState, string source, string customerId, string portalUrl, class Microsoft.Azure.Management.OperationalInsights.Models.Sku sku, valuetype System.Nullable`1&lt;int32&gt; retentionInDays, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Sku,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.Workspace : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Sku * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.Workspace (location, id, name, type, tags, provisioningState, source, customerId, portalUrl, sku, retentionInDays, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="customerId" Type="System.String" />
        <Parameter Name="portalUrl" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.OperationalInsights.Models.Sku" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">Speicherort von Ressourcen</param>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="tags">Ressourcentags</param>
        <param name="provisioningState">Der Bereitstellungsstatus des Arbeitsbereichs. Folgende Werte sind möglich: "Erstellen", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "Löschen", "ProvisioningAccount"</param>
        <param name="source">Die Quelle des Arbeitsbereichs.  Datenquelle definieren, in dem der Arbeitsbereich erstellt wurde. "Azure" bedeutet, dass er in Azure erstellt wurde.  "External" bedeutet, dass sie über die Operational Insights-Portal erstellt wurde. Dieser Wert wird auf der Dienstseite und auf der Clientseite schreibgeschützt festgelegt.</param>
        <param name="customerId">Die ID, die mit dem Arbeitsbereich verknüpft sind. Ermöglicht das Festlegen dieses Werts zum Zeitpunkt der Erstellung Arbeitsbereich erstellt wird, um zu einem vorhandenen Arbeitsbereich verknüpft sein.</param>
        <param name="portalUrl">Die URL des Operational Insights-Portal für diesen Arbeitsbereich.  Dieser Wert wird auf der Dienstseite und auf der Clientseite schreibgeschützt festgelegt.</param>
        <param name="sku">Die SKU des Arbeitsbereichs.</param>
        <param name="retentionInDays">Der Arbeitsbereich datenaufbewahrung in Tagen.
            -1 bedeutet eine unbegrenzte Beibehaltungsdauer für die unbegrenzte Sku. 730 Tagen wird die maximal zulässige Anzahl für alle anderen Skus. </param>
        <param name="eTag">Das ETag des Arbeitsbereichs.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Arbeitsbereich.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomerId">
      <MemberSignature Language="C#" Value="public string CustomerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.CustomerId" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomerId As String" />
      <MemberSignature Language="F#" Value="member this.CustomerId : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.CustomerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID, die mit dem Arbeitsbereich verknüpft sind.  Ermöglicht das Festlegen dieses Werts zum Zeitpunkt der Erstellung Arbeitsbereich erstellt wird, um zu einem vorhandenen Arbeitsbereich verknüpft sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das ETag des Arbeitsbereichs.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PortalUrl">
      <MemberSignature Language="C#" Value="public string PortalUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PortalUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.PortalUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property PortalUrl As String" />
      <MemberSignature Language="F#" Value="member this.PortalUrl : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.PortalUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.portalUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL des Operational Insights-Portal für diesen Arbeitsbereich.  Dieser Wert wird auf der Dienstseite und auf der Clientseite schreibgeschützt festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Bereitstellungsstatus des Arbeitsbereichs. Folgende Werte sind möglich: "Erstellen", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "Löschen", "ProvisioningAccount"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.RetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Beibehaltung der Daten im Arbeitsbereich in Tagen fest. -1 bedeutet eine unbegrenzte Beibehaltungsdauer für die unbegrenzte Sku. 730 Tagen wird die maximal zulässige Anzahl für alle anderen Skus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.OperationalInsights.Models.Sku with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die SKU des Arbeitsbereichs.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Quelle des Arbeitsbereichs.  Datenquelle definieren, in dem der Arbeitsbereich erstellt wurde. "Azure" bedeutet, dass er in Azure erstellt wurde. "External" bedeutet, dass sie über die Operational Insights-Portal erstellt wurde. Dieser Wert wird auf der Dienstseite und auf der Clientseite schreibgeschützt festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="workspace.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
  </Members>
</Type>