<Type Name="ServiceDescription" FullName="System.Fabric.Description.ServiceDescription">
  <TypeSignature Language="C#" Value="public abstract class ServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceDescription" />
  <TypeSignature Language="F#" Value="type ServiceDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.StatelessServiceDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.StatefulServiceDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para> Eine ServiceDescription enthält alle Informationen, die zum Erstellen eines Diensts erforderlich sind. </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceDescription (System.Fabric.Description.ServiceDescription other);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Description.ServiceDescription other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceDescription.#ctor(System.Fabric.Description.ServiceDescription)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (other As ServiceDescription)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceDescription : System.Fabric.Description.ServiceDescription -&gt; System.Fabric.Description.ServiceDescription" Usage="new System.Fabric.Description.ServiceDescription other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Description.ServiceDescription" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>Die Beschreibung des Diensts aus der Parameter kopiert werden.</para>
        </param>
        <summary>
          <para>
            Instanziiert eine <see cref="T:System.Fabric.Description.ServiceDescription" /> mit Parametern aus einer anderen Klasse <see cref="T:System.Fabric.Description.ServiceDescription" /> Objekt.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceDescription (System.Fabric.Description.ServiceDescriptionKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Description.ServiceDescriptionKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceDescription.#ctor(System.Fabric.Description.ServiceDescriptionKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As ServiceDescriptionKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceDescription : System.Fabric.Description.ServiceDescriptionKind -&gt; System.Fabric.Description.ServiceDescription" Usage="new System.Fabric.Description.ServiceDescription kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Description.ServiceDescriptionKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para>Beschreiben Sie die Art der Diensttyp.</para>
        </param>
        <summary>
          <para>Initialisiert eine Instanz von <see cref="T:System.Fabric.Description.ServiceDescription" /> mit Dienstart.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ServiceDescription.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den URI der Anwendung fest.</para>
        </summary>
        <value>
          <para>Der Anwendungsname.</para>
        </value>
        <remarks>
          <para>Dies ist der eindeutige Name einer Anwendung und wird verwendet, um gruppendienste zusammen für die Verwaltung. Das Schema muss "Fabric: /" und der Anwendungsname muss ein Präfix des Dienstnamens sein.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Correlations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt; Correlations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServiceCorrelationDescription&gt; Correlations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.Correlations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Correlations As IList(Of ServiceCorrelationDescription)" />
      <MemberSignature Language="F#" Value="member this.Correlations : System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt;" Usage="System.Fabric.Description.ServiceDescription.Correlations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft die Liste der <see cref="T:System.Fabric.Description.ServiceCorrelationDescription" />s, die beschreiben, das die Korrelationen dieses Diensts mit anderen Diensten.
            </para>
        </summary>
        <value>
          <para>Gibt die Liste der Beschreibungen der Korrelation.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMoveCost">
      <MemberSignature Language="C#" Value="public System.Fabric.MoveCost DefaultMoveCost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.MoveCost DefaultMoveCost" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.DefaultMoveCost" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMoveCost As MoveCost" />
      <MemberSignature Language="F#" Value="member this.DefaultMoveCost : System.Fabric.MoveCost with get, set" Usage="System.Fabric.Description.ServiceDescription.DefaultMoveCost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            Ruft ab oder legt den Standardwert <see cref="T:System.Fabric.MoveCost" /> Wert für den Dienst.
            </para>
        </summary>
        <value>
          <para> Die Standardeinstellung <see cref="T:System.Fabric.MoveCost" /> Wert, der für den Dienst festgelegt werden muss.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[] with get, set" Usage="System.Fabric.Description.ServiceDescription.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder die Initialisierungsdaten, die übergeben werden bei der Erstellung an Dienstinstanzen oder Replikate legt sie fest.</para>
        </summary>
        <value>
          <para>Gibt die Initialisierungsdaten zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultMoveCostSpecified">
      <MemberSignature Language="C#" Value="public bool IsDefaultMoveCostSpecified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDefaultMoveCostSpecified" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.IsDefaultMoveCostSpecified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultMoveCostSpecified As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDefaultMoveCostSpecified : bool" Usage="System.Fabric.Description.ServiceDescription.IsDefaultMoveCostSpecified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            Ruft ab, ob ein standardmäßiges <see cref="T:System.Fabric.MoveCost" /> für den Dienst angegeben wird.
            </para>
        </summary>
        <value>
          <para>Ein Flag, der angibt, ob ein standardmäßiges <see cref="T:System.Fabric.MoveCost" /> für den Dienst angegeben wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceDescriptionKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServiceDescriptionKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ServiceDescriptionKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Description.ServiceDescriptionKind" Usage="System.Fabric.Description.ServiceDescription.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceDescriptionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Art des Diensts (z. B. "Stateful" oder "Stateless") für diesen Dienst ab.</para>
        </summary>
        <value>
          <para>Die Art des Diensts.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Property Metrics As KeyedCollection(Of String, ServiceLoadMetricDescription)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceLoadMetricDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceDescription.Metrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.ServiceLoadMetricDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft ab oder legt die schlüsselgebundene Auflistung der <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />s, die die lastmetriken definiert für diesen Dienst beschreiben.
            </para>
        </summary>
        <value>
          <para>Gibt die Auflistung der Last metrische Beschreibungen zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionSchemeDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.PartitionSchemeDescription PartitionSchemeDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.PartitionSchemeDescription PartitionSchemeDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.PartitionSchemeDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionSchemeDescription As PartitionSchemeDescription" />
      <MemberSignature Language="F#" Value="member this.PartitionSchemeDescription : System.Fabric.Description.PartitionSchemeDescription with get, set" Usage="System.Fabric.Description.ServiceDescription.PartitionSchemeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionSchemeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Partition Scheme-Beschreibung für diesen Dienst verwendet werden soll.</para>
        </summary>
        <value>
          <para>Das Partitionsschema für den Dienst verwendet werden soll.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementConstraints">
      <MemberSignature Language="C#" Value="public string PlacementConstraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlacementConstraints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.PlacementConstraints" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementConstraints As String" />
      <MemberSignature Language="F#" Value="member this.PlacementConstraints : string with get, set" Usage="System.Fabric.Description.ServiceDescription.PlacementConstraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> Ruft ab oder legt die platzierungsbeschränkungen für diesen Dienst.</para>
        </summary>
        <value>
          <para> Gibt die platzierungsbeschränkungen zurück.</para>
        </value>
        <remarks>
          <para>Platzierungsbeschränkungen sind boolesche Anweisungen, die ermöglichen es Diensten, wählen Sie für bestimmte Knoteneigenschaften (und die Werte dieser Eigenschaften), um zu steuern, wo es zulässig, sie platzieren ist.  Eigenschaften des Knotens sind Schlüssel-Wert-Paare, die einige zusätzliche Metadaten über einen Knoten, in der Regel im Zusammenhang mit den Hardwarefunktionen des Knotens zu definieren.  Beispiele für Hardwareeigenschaften, die als Eigenschaften des Knotens verfügbar gemacht werden könnten sind "HasDisk", "%MemorySize", "StorageSize", "" NumberOfCores "" usw. an.  Wenn Sie einen Dienst bereitstellen, kann ein Administrator definieren, die Eigenschaften, denen der Dienst bemüht sowie einfachen booleschen Operatoren die Anforderungen für die Werte dieser Eigenschaften zu definieren.  "Ex": (HasDisk == True &amp; &amp; %MemorySize&gt;= 2048).  Während der Laufzeit wird Service Fabric-Lastenausgleich nur Dienste auf Knoten platzieren, die Eigenschaften mit Werten verfügen, die erforderlich sind, durch den Dienst übereinstimmt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt; PlacementPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServicePlacementPolicyDescription&gt; PlacementPolicies" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.PlacementPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PlacementPolicies As IList(Of ServicePlacementPolicyDescription)" />
      <MemberSignature Language="F#" Value="member this.PlacementPolicies : System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt;" Usage="System.Fabric.Description.ServiceDescription.PlacementPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            Ruft die Liste der <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" />s, die die Richtlinien für die dienstplatzierung für diesen Dienst beschreiben.
            </para>
        </summary>
        <value>
          <para>Gibt die Liste der Platzierung richtlinienbeschreibungen zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDnsName">
      <MemberSignature Language="C#" Value="public string ServiceDnsName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceDnsName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServiceDnsName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDnsName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceDnsName : string with get, set" Usage="System.Fabric.Description.ServiceDescription.ServiceDnsName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft ab oder legt die DNS-Name des Diensts. Wenn dies angegeben ist, und klicken Sie dann den Dienst kann, über den DNS-Namen anstelle von zugegriffen werden <see cref="P:System.Fabric.Description.ServiceDescription.ServiceName" />.
            </para>
        </summary>
        <value>
          <para>Der DNS-Name des Diensts oder <c>null</c> , wenn der Dienst angegebenen DNS-Namen hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri with get, set" Usage="System.Fabric.Description.ServiceDescription.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den URI des Diensts fest.</para>
        </summary>
        <value>
          <para>Der Name des Diensts.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePackageActivationMode As ServicePackageActivationMode" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationMode : System.Fabric.Description.ServicePackageActivationMode with get, set" Usage="System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            Ruft ab oder legt die <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> eines Diensts.
            </para>
        </summary>
        <value>
          <para> 
            Ein <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> -Enumeration, die Aktivierungsmodus des Dienstpakets darstellt, enthält die <see cref="P:System.Fabric.Description.ServiceDescription.ServiceTypeName" /> und wird aktiviert werden, um die Replikate oder Instanzen des Diensts beschrieben, die von diesem host <see cref="T:System.Fabric.Description.ServiceDescription" /> Objekt. Finden Sie unter <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> Weitere Details.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string with get, set" Usage="System.Fabric.Description.ServiceDescription.ServiceTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Dienstnamen für den Typ.</para>
        </summary>
        <value>
          <para>Den Namen des Diensttyps.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>