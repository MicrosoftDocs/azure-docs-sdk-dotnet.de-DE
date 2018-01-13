<Type Name="ServiceGroupMemberDescription" FullName="System.Fabric.Description.ServiceGroupMemberDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupMemberDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupMemberDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceGroupMemberDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupMemberDescription" />
  <TypeSignature Language="F#" Value="type ServiceGroupMemberDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibt einen Dienst, der einer Dienstgruppe angehört.  </para>
    </summary>
    <remarks>
      <para>Ein <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> enthält einen Teil einer normalen zustandslose oder zustandsbehaftete dienstbeschreibung. Diese Felder sind für den Dienst in der Gruppe. Andere Felder, die in eine normale dienstbeschreibung, z. B. Partitionierung Informationen vorhanden sind, werden Eigenschaften der Dienstgruppe über seine <see cref="T:System.Fabric.Description.ServiceGroupDescription" />.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupMemberDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupMemberDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Erstellt ein leeres <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />-Objekt.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupMemberDescription (string serviceTypeName, Uri serviceName, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupMemberDescription.#ctor(System.String,System.Uri,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceTypeName As String, serviceName As Uri, initializationData As Byte())" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceGroupMemberDescription : string * Uri * byte[] -&gt; System.Fabric.Description.ServiceGroupMemberDescription" Usage="new System.Fabric.Description.ServiceGroupMemberDescription (serviceTypeName, serviceName, initializationData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Diensttypname des Gruppenmitglieds Dienst.</para>
        </param>
        <param name="serviceName">
          <para>Der vollqualifizierte Name für das Element festgelegt werden soll. Wenn der Name der Fabric ist z. B.: / G1 mit dem Element M1 handelt, geben Sie der vollständige Namen Fabric: / G&amp;#1;M1.</para>
        </param>
        <param name="initializationData">
          <para>Das Byte [], das als die Initialisierungsdaten mit des Mitglieds Factory bereitgestellt wird.</para>
        </param>
        <summary>
          <para>Erstellt ein <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> -Objekt und initialisiert sie mit den angegebenen Parametern.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupMemberDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[] with get, set" Usage="System.Fabric.Description.ServiceGroupMemberDescription.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Performance", "CA1819:PropertiesShouldNotReturnArrays", Justification="Manipulation of byte[] does not have any effect on the ServiceDescription already registered")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Initialisierungsdaten für dieses Gruppenmitglied Dienst fest.</para>
        </summary>
        <value>
          <para>die Initialisierungsdaten für dieses Gruppenmitglied Dienst.</para>
        </value>
        <remarks>
          <para>Diese Informationen als die Gruppe dienstfactory übergeben wird, um den Dienst-Factorys, die während der Erstellung als Initialisierungsdaten für das Objekt entsprechen Instanzen dieses Gruppenmitglied von Service, ähnlich wie andere Initialisierungsdaten beim normalen zustandslose übergeben werden oder zustandsbehaftete Dienstinstanzen werden erstellt.</para>
        </remarks>
        <altmember cref="M:System.Fabric.IStatelessServiceFactory.CreateInstance(System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
        <altmember cref="M:System.Fabric.IStatefulServiceFactory.CreateReplica(System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
        <altmember cref="P:System.Fabric.Description.ServiceDescription.InitializationData" />
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupMemberDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metrics As IList(Of ServiceLoadMetricDescription)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceLoadMetricDescription&gt;" Usage="System.Fabric.Description.ServiceGroupMemberDescription.Metrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceLoadMetricDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Auflistung der <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" /> Objekte für diesen Dienst. Die metrikauflistung enthält die <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" /> Objekte, die für diesen Dienst sind.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Collections.Generic.IList`1" /> vom Typ <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupMemberDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri with get, set" Usage="System.Fabric.Description.ServiceGroupMemberDescription.ServiceName" />
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
          <para>Ruft ab oder legt den Namen des Diensts in der Dienstgruppe fest.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Uri" /> , die den Dienstnamen darstellt.</para>
        </value>
        <remarks>
          <para>Dienste werden unabhängig voneinander in der Dienstgruppe benannt. Dieser Name wird als Teil der stabilen Fabric-verwendet, um den Dienst zu beheben. Beispielsweise wird der den Namen der Dienstgruppe "Fabric: / AuswahlgruppeEin" und der Dienstnamen bereitgestellt wird, ist hier "svc1", und klicken Sie dann ein Client sollte den Namen auflösen "Fabric: / AuswahlgruppeEin #svc1" diesen Dienst aufgelöst.</para>
        </remarks>
        <altmember cref="T:System.Fabric.Description.ServiceDescription" />
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupMemberDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string with get, set" Usage="System.Fabric.Description.ServiceGroupMemberDescription.ServiceTypeName" />
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
          <para>Ruft ab, oder legt Sie den Diensttyp des dieses Gruppenmitglied Dienst fest.</para>
        </summary>
        <value>
          <para>Der Diensttypname.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>