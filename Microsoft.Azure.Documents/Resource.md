<Type Name="Resource" FullName="Microsoft.Azure.Documents.Resource">
  <TypeSignature Language="C#" Value="public abstract class Resource : Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Resource extends Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Resource&#xA;Inherits JsonSerializable" />
  <TypeSignature Language="F#" Value="type Resource = class&#xA;    inherit JsonSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> 
             Stellt einen abstrakte Ressourcentyp im Azure-Cosmos-DB-Dienst dar.
             Alle Azure-Cosmos-DB-Ressourcen, wie z. B. <see cref="T:Microsoft.Azure.Documents.Database" />, <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, und <see cref="T:Microsoft.Azure.Documents.Document" /> dieser abstrakten Typ erweitern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Resource ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Resource" /> Klasse für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Resource (Microsoft.Azure.Documents.Resource resource);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Resource resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.#ctor(Microsoft.Azure.Documents.Resource)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Resource : Microsoft.Azure.Documents.Resource -&gt; Microsoft.Azure.Documents.Resource" Usage="new Microsoft.Azure.Documents.Resource resource" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resource" Type="Microsoft.Azure.Documents.Resource" />
      </Parameters>
      <Docs>
        <param name="resource">To be added.</param>
        <summary>
            Kopierkonstruktor für eine <see cref="T:Microsoft.Azure.Documents.Resource" /> im Azure-Cosmos-DB-Dienst verwendet.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AltLink">
      <MemberSignature Language="C#" Value="public string AltLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AltLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.AltLink" />
      <MemberSignature Language="VB.NET" Value="Public Property AltLink As String" />
      <MemberSignature Language="F#" Value="member this.AltLink : string with get, set" Usage="Microsoft.Azure.Documents.Resource.AltLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Alt-Verknüpfung der Ressource aus dem Azure-Cosmos-DB-Dienst zugeordnet.
            </summary>
        <value>Die Alt-Verknüpfung der Ressource zugeordnet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Documents.Resource.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Entitätstag aus dem Azure-Cosmos-DB-Dienst zur Ressource zugeordnete ab.
            </summary>
        <value>
            Die Entitäts-Tag, das der Ressource zugeordnet ist.
            </value>
        <remarks>
            Etags mit werden für parallelitätsprüfung beim Aktualisieren von Ressourcen verwendet. 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyValue&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetPropertyValue&lt;T&gt; (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetPropertyValue&lt;T&gt;(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.GetPropertyValue``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyValue(Of T) (propertyName As String) As T" />
      <MemberSignature Language="F#" Value="member this.GetPropertyValue : string -&gt; 'T" Usage="resource.GetPropertyValue propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ der Eigenschaft.</typeparam>
        <param name="propertyName">Der Name der Eigenschaft.</param>
        <summary>
            Ruft den angegebenen Eigenschaftennamen aus dem Azure-Cosmos-DB-Dienst zugeordneten Eigenschaftswert ab.
            </summary>
        <returns>Der Eigenschaftswert.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public virtual string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.Id" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Documents.Resource.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
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
            Ruft ab oder legt die Id der Ressource in der Azure-Cosmos-DB-Dienst fest.
            </summary>
        <value>Die Id der Ressource zugeordnet ist.</value>
        <remarks>
          <para>
            Jede Ressource in einem Azure-Cosmos-DB-Datenbank-Konto muss über einen eindeutigen Bezeichner verfügen. Im Gegensatz zu <see cref="P:Microsoft.Azure.Documents.Resource.ResourceId" />, die intern festgelegt ist, wird diese Id wird vom Benutzer festlegbaren und unveränderlich ist.
            </para>
          <para>
            Bei der Arbeit mit Dokumentressourcen bieten sie ebenfalls diese Id-Eigenschaft festgelegt werden. Wenn eine Id nicht vom Benutzer bereitgestellt wird das SDK automatisch eine neue GUID generiert und weisen den Wert dieser Eigenschaft vor dem das Dokument in der Datenbank beibehalten. Sie können diese Id der automatischen Generierung überschreiben, indem Sie den DisableAutomaticIdGeneration-Parameter festlegen, auf die <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> Instanz auf "true".
            Dadurch wird verhindert, dass das SDK generieren neue Ids. 
            </para>
          <para>
            Die folgenden Zeichen sind beschränkt und kann nicht in die Id-Eigenschaft verwendet werden: '/', '\\','?', '#'
             </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public virtual string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Documents.Resource.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_rid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ressourcen-Id der Ressource in der Azure-Cosmos-Datenbank zugeordnet.
            </summary>
        <value>
            Die Ressourcen-Id der Ressource zugeordnet.
            </value>
        <remarks>
            Eine Ressourcen-Id ist der eindeutige, unveränderliche-Bezeichner, die jeder Azure-Cosmos-DB-Ressource zugewiesen ist, ob eine Datenbank, eine Auflistung oder ein Dokument ist.
            Diese Ressourcen-Ids werden verwendet, wenn Sie SelfLinks, eine statische adressierbaren Uri für jede Ressource innerhalb eines Kontos für Datenbank erstellen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SelfLink">
      <MemberSignature Language="C#" Value="public string SelfLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelfLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.SelfLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelfLink As String" />
      <MemberSignature Language="F#" Value="member this.SelfLink : string" Usage="Microsoft.Azure.Documents.Resource.SelfLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_self")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, der Self-link der Ressource mit dem der Dienst Azure-Cosmos-Datenbank zugeordnet.
            </summary>
        <value>Der Self-link der Ressource zugeordnet.</value>
        <remarks>
            Self-link ist eine statische adressierbaren Uri für jede Ressource innerhalb eines Kontos für Datenbank und das Azure-Cosmos-DB-Ressourcenmodell folgt.
            Beispiel: Self-link für ein Dokument kann Dbs/Db_resourceid/colls/Coll_resourceid/Dokumente/Doc_resourceid sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertyValue">
      <MemberSignature Language="C#" Value="public void SetPropertyValue (string propertyName, object propertyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetPropertyValue(string propertyName, object propertyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.SetPropertyValue(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetPropertyValue (propertyName As String, propertyValue As Object)" />
      <MemberSignature Language="F#" Value="member this.SetPropertyValue : string * obj -&gt; unit" Usage="resource.SetPropertyValue (propertyName, propertyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="propertyValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="propertyName">Der Name der Eigenschaft.</param>
        <param name="propertyValue">Der Eigenschaftswert.</param>
        <summary>
            Legt den angegebenen Eigenschaftennamen im Azure-Cosmos-DB-Dienst zugeordneten Eigenschaftswert fest.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public virtual DateTime Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime" Usage="Microsoft.Azure.Documents.Resource.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.UnixDateTimeConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_ts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitstempel der letzten Änderung der Ressource mit dem der Dienst Azure-Cosmos-Datenbank zugeordnet.
            </summary>
        <value>Der Zeitstempel der letzten Änderung der Ressource zugeordnet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToByteArray">
      <MemberSignature Language="C#" Value="public byte[] ToByteArray ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] ToByteArray() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.ToByteArray" />
      <MemberSignature Language="VB.NET" Value="Public Function ToByteArray () As Byte()" />
      <MemberSignature Language="F#" Value="member this.ToByteArray : unit -&gt; byte[]" Usage="resource.ToByteArray " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Serialisieren Sie in ein Bytearray über SaveTo für den Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>