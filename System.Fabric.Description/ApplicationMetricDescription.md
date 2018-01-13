<Type Name="ApplicationMetricDescription" FullName="System.Fabric.Description.ApplicationMetricDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationMetricDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationMetricDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationMetricDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationMetricDescription" />
  <TypeSignature Language="F#" Value="type ApplicationMetricDescription = class" />
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
            Gibt die Anwendungskapazität für eine Metrik an.
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:System.Fabric.Description.ApplicationDescription" />
    <altmember cref="T:System.Fabric.Description.ApplicationUpdateDescription" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationMetricDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationMetricDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodeCapacity">
      <MemberSignature Language="C#" Value="public long MaximumNodeCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaximumNodeCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodeCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.MaximumNodeCapacity : int64 with get, set" Usage="System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Knotenkapazität für Service Fabric-Anwendung.
            </summary>
        <value>
          <para>
            Gibt die maximale Last für eine Instanz dieser Anwendung auf einem einzelnen Knoten.
            Auch wenn die Kapazität des Knotens größer als dieser Wert ist, wird Service Fabric die Gesamtlast der Dienste in der Anwendung auf jedem Knoten mit diesem Wert beschränkt.
            </para>
          <para>Wenn auf NULL gesetzt, Kapazität für die Metrik auf jedem Knoten unbegrenzt ist.</para>
          <para>
            Beim Erstellen einer neuen Anwendung mit der Anwendungskapazität definiert, des Produkts der <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> und dieser Wert muss immer kleiner als oder gleich <see cref="P:System.Fabric.Description.ApplicationMetricDescription.TotalApplicationCapacity" />.
            </para>
          <para>
            Beim Aktualisieren der vorhandenen Anwendung mit Anwendungskapazität, das Produkt der <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> und dieser Wert muss immer kleiner als oder gleich <see cref="P:System.Fabric.Description.ApplicationMetricDescription.TotalApplicationCapacity" />.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationMetricDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="System.Fabric.Description.ApplicationMetricDescription.Name" />
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
            Ruft ab oder legt den Namen der Metrik.
            </summary>
        <value>
            Der Name der Metrik.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeReservationCapacity">
      <MemberSignature Language="C#" Value="public long NodeReservationCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeReservationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationMetricDescription.NodeReservationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeReservationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeReservationCapacity : int64 with get, set" Usage="System.Fabric.Description.ApplicationMetricDescription.NodeReservationCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Reservierung Knotenkapazität für Service Fabric-Anwendung.
            </summary>
        <value>
          <para>
            Gibt die Menge der Metrik laden, wodurch die reserviert ist in Knoten, die Instanzen dieser Anwendung verfügen.
            Wenn <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" /> angegeben wird, wird das Produkt dieser Werte die Kapazität für die Anwendung im Cluster reserviert wird.
            </para>
          <para>
            Wenn auf NULL gesetzt, keine Kapazität für die Metrik reserviert ist.
            </para>
          <para>
            Beim Festlegen der Anwendungskapazität (<see cref="T:System.Fabric.Description.ApplicationDescription" />) oder beim Aktualisieren der Anwendungskapazität ((<see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />) dieser Wert muss kleiner als oder gleich sein <see cref="P:System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" /> für jede Metrik.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalApplicationCapacity">
      <MemberSignature Language="C#" Value="public long TotalApplicationCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalApplicationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationMetricDescription.TotalApplicationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalApplicationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.TotalApplicationCapacity : int64 with get, set" Usage="System.Fabric.Description.ApplicationMetricDescription.TotalApplicationCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtkapazität metrische für Service Fabric-Anwendung.
            </summary>
        <value>
          <para>
            Gibt die Gesamtkapazität Metrik für diese Anwendung im Cluster an.
            Service Fabric versucht, die die Summe der verschiedener Dienste in der Anwendung auf diesen Wert zu beschränken.
            </para>
          <para>
            Beim Erstellen einer neuen Anwendung mit der Anwendungskapazität definiert, des Produkts der <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> und <see cref="P:System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" /> muss immer kleiner oder gleich diesem Wert sein.
            </para>
          <para>
            Beim Erstellen einer neuen Anwendung mit der Anwendungskapazität definiert, des Produkts der <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> und <see cref="P:System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" /> muss immer kleiner oder gleich diesem Wert sein.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>