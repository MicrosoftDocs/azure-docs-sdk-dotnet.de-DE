<Type Name="FailoverGroup" FullName="Microsoft.Azure.Management.Sql.Models.FailoverGroup">
  <TypeSignature Language="C#" Value="public class FailoverGroup : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverGroup extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverGroup&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type FailoverGroup = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine Failover-Gruppe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der FailoverGroup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroup (Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint readWriteEndpoint, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; partnerServers, string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint readOnlyEndpoint = null, string replicationRole = null, string replicationState = null, System.Collections.Generic.IList&lt;string&gt; databases = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint readWriteEndpoint, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; partnerServers, string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint readOnlyEndpoint, string replicationRole, string replicationState, class System.Collections.Generic.IList`1&lt;string&gt; databases) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroup.#ctor(Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.PartnerInfo},System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (readWriteEndpoint As FailoverGroupReadWriteEndpoint, partnerServers As IList(Of PartnerInfo), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional readOnlyEndpoint As FailoverGroupReadOnlyEndpoint = null, Optional replicationRole As String = null, Optional replicationState As String = null, Optional databases As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FailoverGroup : Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="new Microsoft.Azure.Management.Sql.Models.FailoverGroup (readWriteEndpoint, partnerServers, id, name, type, location, tags, readOnlyEndpoint, replicationRole, replicationState, databases)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="readWriteEndpoint" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint" />
        <Parameter Name="partnerServers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="readOnlyEndpoint" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint" />
        <Parameter Name="replicationRole" Type="System.String" />
        <Parameter Name="replicationState" Type="System.String" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="readWriteEndpoint">Lese-/ Schreibzugriff Endpunkt der Gruppeninstanz Failover.</param>
        <param name="partnerServers">Liste der Partner-Serverinformationen für die Failover-Gruppe.</param>
        <param name="id">Ressourcen-ID</param>
        <param name="name">Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="location">Der Ressourcenspeicherort.</param>
        <param name="tags">Ressourcentags.</param>
        <param name="readOnlyEndpoint">Nur-Lese Endpunkt der Gruppeninstanz Failover.</param>
        <param name="replicationRole">Lokale replikationsrolle der Gruppeninstanz Failover. Folgende Werte sind möglich: 'Primary', 'Sekundären'</param>
        <param name="replicationState">Der Replikationsstatus der Gruppeninstanz Failover.</param>
        <param name="databases">Die Liste der Datenbanken in der Gruppe "Failover".</param>
        <summary>
            Initialisiert eine neue Instanz der FailoverGroup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Databases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.Databases" />
      <MemberSignature Language="VB.NET" Value="Public Property Databases As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Datenbanken in der Gruppe "Failover" fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Position der Ressource ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; PartnerServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; PartnerServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.PartnerServers" />
      <MemberSignature Language="VB.NET" Value="Public Property PartnerServers As IList(Of PartnerInfo)" />
      <MemberSignature Language="F#" Value="member this.PartnerServers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.PartnerServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Partner-Serverinformationen für die Failover-Gruppe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadOnlyEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint ReadOnlyEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint ReadOnlyEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReadOnlyEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadOnlyEndpoint As FailoverGroupReadOnlyEndpoint" />
      <MemberSignature Language="F#" Value="member this.ReadOnlyEndpoint : Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReadOnlyEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readOnlyEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-nur-Lese-Endpunkt der Gruppeninstanz Failover.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadWriteEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint ReadWriteEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint ReadWriteEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReadWriteEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadWriteEndpoint As FailoverGroupReadWriteEndpoint" />
      <MemberSignature Language="F#" Value="member this.ReadWriteEndpoint : Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReadWriteEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readWriteEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen von Lese-/ Schreibzugriff-Endpunkt der Gruppeninstanz Failover.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationRole">
      <MemberSignature Language="C#" Value="public string ReplicationRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReplicationRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationRole As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationRole : string" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReplicationRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicationRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Failover-Gruppeninstanz lokale replikationsrolle ab.
            Folgende Werte sind möglich: 'Primary', 'Sekundären'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationState">
      <MemberSignature Language="C#" Value="public string ReplicationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReplicationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationState As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationState : string" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReplicationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Replikationsstatus der Gruppeninstanz Failover ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder Ressourcen-Tags definiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="failoverGroup.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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