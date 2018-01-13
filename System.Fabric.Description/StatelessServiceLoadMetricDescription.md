<Type Name="StatelessServiceLoadMetricDescription" FullName="System.Fabric.Description.StatelessServiceLoadMetricDescription">
  <TypeSignature Language="C#" Value="public sealed class StatelessServiceLoadMetricDescription : System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatelessServiceLoadMetricDescription extends System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatelessServiceLoadMetricDescription&#xA;Inherits ServiceLoadMetricDescription" />
  <TypeSignature Language="F#" Value="type StatelessServiceLoadMetricDescription = class&#xA;    inherit ServiceLoadMetricDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceLoadMetricDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Gibt eine Metrik für eines zustandslosen Diensts an.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatelessServiceLoadMetricDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceLoadMetricDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultLoad">
      <MemberSignature Language="C#" Value="public int DefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatelessServiceLoadMetricDescription.DefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.DefaultLoad : int with get, set" Usage="System.Fabric.Description.StatelessServiceLoadMetricDescription.DefaultLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder Festlegen der Standarddauer der Auslastung, die diesen Dienst für die Metrik generiert wird.</para>
        </summary>
        <value>
          <para>Die Standarddauer an der Auslastung, die diesen Dienst für die Metrik generiert wird.</para>
        </value>
        <remarks>
          <para>Angeben von Standardwerten der Last für benutzerdefinierte Metriken kann Ressourcen-Manager von Service Fabric Cluster Services effizient zu platzieren, wenn sie zuerst erstellt werden.
            Wenn Standard Laden nicht angegeben, dass Service Fabric-Cluster-Ressourcen-Manager keine Last für dieses Replikat angenommen, bis der Dienst seine laden meldet.
            <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceLoadMetricDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="statelessServiceLoadMetricDescription.ToString " />
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
            Details der Schöndruck <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />.</returns>
        <remarks>To be added.</remarks>
        <example>
            CPU, hoch, 90
            </example>
      </Docs>
    </Member>
  </Members>
</Type>