<Type Name="ITableEntity" FullName="Microsoft.WindowsAzure.Storage.Table.ITableEntity">
  <TypeSignature Language="C#" Value="public interface ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITableEntity" />
  <TypeSignature Language="F#" Value="type ITableEntity = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine Schnittstelle, die für tabellenentitätstypen erforderlich sind. Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> Schnittstelle deklariert Getter- und Setter-Methoden für die erforderlichen Entitätseigenschaften und <see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" /> und <see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> Methoden für die Serialisierung und Deserialisierung aller Entitätseigenschaften, die ein Eigenschaftenwörterbuch verwenden. Erstellen von Klassen implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> Eigenschaftspeicher, abrufen, Serialisierung und Deserialisierung anpassen und zusätzlichen benutzerdefinierte Logik für eine Tabellenentität bereitzustellen.
            </summary>
    <remarks>
      <para>Die speicherclientbibliothek enthält zwei Implementierungen von <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> , die für einfache Eigenschaftenzugriff und Serialisierung bereitstellen:</para>
      <para>
        <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />implementiert <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> und bietet ein einfaches Eigenschaftenwörterbuch zum Speichern und Abrufen von Eigenschaften. Verwenden einer <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> für den einfachen Zugriff auf Entitätseigenschaften, wenn nur eine Teilmenge der Eigenschaften (z. B. durch eine select-Klausel in einer Abfrage) zurückgegeben werden, oder für Szenarien, in denen die Abfrage mehrere Entitätstypen mit verschiedenen Eigenschaften zurückgeben kann. Sie können auch dieses Typs verwenden, um massentabellenaktualisierungen von heterogenen Entitäten ohne Verlust von Eigenschaftsinformationen auszuführen.</para>
      <para>
        <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />ist eine Implementierung von <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> , verwendet reflektionsbasierte Serialisierung und Deserialisierung Verhalten in seiner <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" /> und <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> Methoden. 
            <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />-abgeleitete Klassen mit Methoden, die Dateinamenskonvention für Typen- und Namenskonvention werden automatisch serialisiert und deserialisiert. <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />-abgeleitete Klassen müssen auch eine öffentliche Get-able- und Set-able-Eigenschaft eines Typs, die vom Microsoft Azure-Tabellendienst unterstützt angeben.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.ITableEntity.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das aktuelle ETag der Entität.  Legen Sie diesen Wert auf "*" um eine Entität als Teil eines Updatevorgangs Blind zu überschreiben.
            </summary>
        <value>Zeitstempel der Entität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.ITableEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Partitionsschlüssel der Entität.
            </summary>
        <value>Der Partitionsschlüssel der Entität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="iTableEntity.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">Das Wörterbuch mit zeichenfolgeneigenschaftsnamen für <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte deserialisiert und gespeichert, die in dieser tabellenentitätsinstanz.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Füllt die Eigenschaften der Entität aus der <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte in der <paramref name="properties" /> Wörterbuch. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.ITableEntity.RowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Zeilenschlüssel der Entität.
            </summary>
        <value>Zeilenschlüssel der Entität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.ITableEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitstempel der Entität.
            </summary>
        <value>Zeitstempel der Entität. Die Eigenschaft wird vom Microsoft Azure-Tabellendienst aufgefüllt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity (Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity(class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="iTableEntity.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Serialisiert die <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftennamen zugeordnet <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte aus der Entitätsinstanz.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt von Eigenschaftennamen <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> -Datentypwerte, die durch Serialisieren dieser tabellenentitätsinstanz erstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>