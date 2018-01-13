<Type Name="SearchService" FullName="Microsoft.Azure.Management.Search.Models.SearchService">
  <TypeSignature Language="C#" Value="public class SearchService : Microsoft.Azure.Management.Search.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchService extends Microsoft.Azure.Management.Search.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.SearchService" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchService&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SearchService = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Search.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibt einen Azure Search-Dienst und seinem aktuellen Status.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SearchService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchService (string location, Microsoft.Azure.Management.Search.Models.Sku sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;int&gt; replicaCount = null, Nullable&lt;int&gt; partitionCount = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; hostingMode = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; status = null, string statusDetails = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.Search.Models.Sku sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;int32&gt; replicaCount, valuetype System.Nullable`1&lt;int32&gt; partitionCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.HostingMode&gt; hostingMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; status, string statusDetails, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.#ctor(System.String,Microsoft.Azure.Management.Search.Models.Sku,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Search.Models.HostingMode},System.Nullable{Microsoft.Azure.Management.Search.Models.SearchServiceStatus},System.String,System.Nullable{Microsoft.Azure.Management.Search.Models.ProvisioningState})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.SearchService : string * Microsoft.Azure.Management.Search.Models.Sku * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; * Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; * string * Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="new Microsoft.Azure.Management.Search.Models.SearchService (location, sku, id, name, type, tags, replicaCount, partitionCount, hostingMode, status, statusDetails, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Search.Models.Sku" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="replicaCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="partitionCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="hostingMode" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;" />
        <Parameter Name="statusDetails" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;" />
      </Parameters>
      <Docs>
        <param name="location">Der geografische Standort der Ressource.
            Diese Angabe muss eines der unterstützten und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.).</param>
        <param name="sku">Die SKU des Search-Dienst, der bestimmt, Preis, Ebenen und Kapazitätsgrenzen.</param>
        <param name="id">Die ID der Ressource. Dies kann mit der Azure-Ressourcen-Manager verwendet werden Ressourcen miteinander verknüpfen.</param>
        <param name="name">Der Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="tags">Tags helfen, die Ressource im Azure-Portal zu kategorisieren.</param>
        <param name="replicaCount">Die Anzahl der Replikate in der Search-Dienst. Wenn angegeben, muss es einen Wert zwischen 1 und 12 einschließlich für standard-SKUs oder zwischen 1 und 3 für SKUs vom Typ basic inklusive.</param>
        <param name="partitionCount">Die Anzahl der Partitionen in der Search-Dienst; Wenn angegeben, kann es 1, 2, 3, 4, 6 oder 12.
            Werte größer als 1 sind nur für standard-SKUs gültig. Für "standard3"-Dienste mit HostingMode "HighDensity" festgelegt werden die zulässigen Werte zwischen 1 und 3 ein.</param>
        <param name="hostingMode">Gilt nur für die SKU standard3.
            Sie können festlegen, dass diese Eigenschaft zum Aktivieren von bis zu 3 – hohe Dichte Partitionen, die bis zu 1.000-Indizes ermöglichen, dies ist sehr viel höher als die maximale Indizes für beliebige andere SKU zulässig. Für die SKU standard3 ist der Wert "Default" oder "HighDensity".
            Für alle anderen SKUs muss dieser Wert "Default" sein. Folgende Werte sind möglich: "Default", "HighDensity"</param>
        <param name="status">Der Status des Suchdiensts. Folgende Werte sind möglich: "wird ausgeführt": die Search-Dienst ausgeführt wird und keine Bereitstellung Vorgänge ausgeführt werden. 'Bereitstellung': der Suchdienst wird bereitgestellt, oder nach oben oder unten skaliert. "deleting": der Suchdienst wird gelöscht. "heruntergestuft": der Suchdienst wird heruntergestuft. Dies kann auftreten, wenn die zugrunde liegenden sucheinheiten nicht fehlerfrei sind. Der Suchdienst ist wahrscheinlich betriebsbereit, aber möglicherweise ist er langsam und einige Anforderungen werden gelöscht. "disabled": der Suchdienst wird deaktiviert. Mit diesem Status lehnt der Dienst alle API-Anforderungen ab. "Fehler": der Suchdienst wird im Status "Fehler". Wenn Ihr Dienst in der eingeschränkter deaktiviert oder Fehler angibt ist, bedeutet dies, dass das Azure Search-Team, das zugrunde liegende Problem untersuchen ist.
            Dedizierte Dienste mit diesen Status sind weiterhin auf Basis der Anzahl der bereitgestellten Sucheinheiten fakturierbar. Folgende Werte sind möglich: "wird ausgeführt", "Bereitstellung", "löschen", "heruntergestuft", "disabled", "Fehler"</param>
        <param name="statusDetails">Die Details des Status des Search-Diensts.</param>
        <param name="provisioningState">Der Status des letzten Vorgangs für die Bereitstellung, die auf der Search-Dienst ausgeführt werden. Die Bereitstellung ist ein vorübergehender Zustand während der Einrichtung der Dienstkapazität. Nach Kapazität eingerichtet ist, wird ProvisioningState auf "erfolgreich abgeschlossen" oder "fehlgeschlagen" geändert. Clientanwendungen können Bereitstellungsstatus (empfohlene Abrufintervall liegt zwischen 30 Sekunden und einer Minute) abrufen, mit der Search-Dienst abrufen Vorgang angezeigt, wenn ein Vorgang abgeschlossen ist. Wenn Sie den kostenlosen Dienst verwenden, neigt dieser Wert als "erfolgreich direkt im Aufruf der Suchdienst erstellen" zurückkehren. Grund hierfür ist, dass der kostenlose Dienst bereits eingerichtete Kapazitäten verwendet. Folgende Werte sind möglich: "erfolgreich abgeschlossen", "Bereitstellung", "fehlgeschlagen"</param>
        <summary>
            Initialisiert eine neue Instanz der SearchService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; HostingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.HostingMode&gt; HostingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.HostingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingMode As Nullable(Of HostingMode)" />
      <MemberSignature Language="F#" Value="member this.HostingMode : Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.HostingMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gilt nur für die SKU standard3. Sie können festlegen, dass diese Eigenschaft zum Aktivieren von bis zu 3 – hohe Dichte Partitionen, die bis zu 1.000-Indizes ermöglichen, dies ist sehr viel höher als die maximale Indizes für beliebige andere SKU zulässig. Für die SKU standard3 ist der Wert "Default" oder "HighDensity". Für alle anderen SKUs muss dieser Wert "Default" sein. Folgende Werte sind möglich: "Default", "HighDensity"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partitionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Partitionen in der Search-Dienst fest. Wenn angegeben, kann es 1, 2, 3, 4, 6 oder 12. Werte größer als 1 sind nur für standard-SKUs gültig. Für "standard3"-Dienste mit HostingMode "HighDensity" festgelegt werden die zulässigen Werte zwischen 1 und 3 ein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.Search.Models.SearchService.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der Status der letzten Operation für die Search-Dienst bereitstellen. Die Bereitstellung ist ein vorübergehender Zustand während der Einrichtung der Dienstkapazität. Nach Kapazität eingerichtet ist, wird ProvisioningState auf "erfolgreich abgeschlossen" oder "fehlgeschlagen" geändert. Clientanwendungen können Bereitstellungsstatus (empfohlene Abrufintervall liegt zwischen 30 Sekunden und einer Minute) abrufen, mit der Search-Dienst abrufen Vorgang angezeigt, wenn ein Vorgang abgeschlossen ist. Wenn Sie den kostenlosen Dienst verwenden, neigt dieser Wert als "erfolgreich direkt im Aufruf der Suchdienst erstellen" zurückkehren. Grund hierfür ist, dass der kostenlose Dienst bereits eingerichtete Kapazitäten verwendet. Folgende Werte sind möglich: "erfolgreich abgeschlossen", "Bereitstellung", "fehlgeschlagen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ReplicaCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ReplicaCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.ReplicaCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ReplicaCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.ReplicaCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicaCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Replikate in der Search-Dienst fest. Wenn angegeben, muss es einen Wert zwischen 1 und 12 einschließlich für standard-SKUs oder zwischen 1 und 3 für SKUs vom Typ basic inklusive.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Search.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Search.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Search.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die SKU des Search-Dienst, der bestimmt, price-Ebene und Kapazitätsgrenzen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of SearchServiceStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;" Usage="Microsoft.Azure.Management.Search.Models.SearchService.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des Suchdiensts ab. Folgende Werte sind möglich: "wird ausgeführt": die Search-Dienst ausgeführt wird und keine Bereitstellung Vorgänge ausgeführt werden. 'Bereitstellung': der Suchdienst wird bereitgestellt, oder nach oben oder unten skaliert. "deleting": der Suchdienst wird gelöscht. "heruntergestuft": der Suchdienst wird heruntergestuft. Dies kann auftreten, wenn die zugrunde liegenden sucheinheiten nicht fehlerfrei sind. Der Suchdienst ist wahrscheinlich betriebsbereit, aber möglicherweise ist er langsam und einige Anforderungen werden gelöscht.
            "disabled": der Suchdienst wird deaktiviert. Mit diesem Status lehnt der Dienst alle API-Anforderungen ab. "Fehler": der Suchdienst wird im Status "Fehler". Wenn Ihr Dienst in der eingeschränkter deaktiviert oder Fehler angibt ist, bedeutet dies, dass das Azure Search-Team, das zugrunde liegende Problem untersuchen ist. Dedizierte Dienste mit diesen Status sind weiterhin auf Basis der Anzahl der bereitgestellten Sucheinheiten fakturierbar. Folgende Werte sind möglich: "wird ausgeführt", "Bereitstellung", "löschen", "heruntergestuft", "disabled", "Fehler"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="Microsoft.Azure.Management.Search.Models.SearchService.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Details des suchen-Dienststatus ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="searchService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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