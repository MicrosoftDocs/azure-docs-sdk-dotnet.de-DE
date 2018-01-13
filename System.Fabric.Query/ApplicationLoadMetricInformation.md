<Type Name="ApplicationLoadMetricInformation" FullName="System.Fabric.Query.ApplicationLoadMetricInformation">
  <TypeSignature Language="C#" Value="public sealed class ApplicationLoadMetricInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationLoadMetricInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationLoadMetricInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationLoadMetricInformation" />
  <TypeSignature Language="F#" Value="type ApplicationLoadMetricInformation = class" />
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
            Stellt die Informationen zum Kapazität und der aktuellen Auslastung für eine Metrik, die Dienste der Anwendung verwenden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationLoadMetricInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadMetricInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationCapacity">
      <MemberSignature Language="C#" Value="public long ApplicationCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ApplicationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ApplicationCapacity : int64" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationCapacity" />
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
            Ruft die gesamte Kapazität für die Metrik ab.
            </summary>
        <value>
            Die gesamte Kapazität, die für die Metrik verfügbar ist, die die Dienste dieser Anwendung verwenden können.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLoad">
      <MemberSignature Language="C#" Value="public long ApplicationLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ApplicationLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationLoad As Long" />
      <MemberSignature Language="F#" Value="member this.ApplicationLoad : int64" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationLoad" />
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
            Ruft die Last für die Metrik an.
            </summary>
        <value>
            Die Gesamtlast, die die Dienste dieser Anwendung verwenden.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.Name" />
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
            Ruft den Namen der Metrik.
            </summary>
        <value>
            Der Name der Metrik.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReservationCapacity">
      <MemberSignature Language="C#" Value="public long ReservationCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReservationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.ReservationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReservationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ReservationCapacity : int64" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.ReservationCapacity" />
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
            Ruft die reservierte Kapazität für die Metrik ab.
            </summary>
        <value>
            Die Ammount der Kapazität, der im Cluster für diese Anwendung reserviert ist.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadMetricInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationLoadMetricInformation.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Details der Schöndruck <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />.
            </para>
        </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />.</returns>
        <remarks>To be added.</remarks>
        <example>
            LoadMetricName: Metric1 ReservationCapacity: ApplicationCapacity 10: 10 ApplicationLoad: 2
            </example>
      </Docs>
    </Member>
  </Members>
</Type>