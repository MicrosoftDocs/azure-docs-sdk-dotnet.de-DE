<Type Name="ApplicationLoadInformation" FullName="System.Fabric.Query.ApplicationLoadInformation">
  <TypeSignature Language="C#" Value="public class ApplicationLoadInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationLoadInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationLoadInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationLoadInformation" />
  <TypeSignature Language="F#" Value="type ApplicationLoadInformation = class" />
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
      <para> Beschreibt das Laden der eine Anwendungsinstanz, die mit abgerufen wird<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String)" /></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationLoadInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLoadMetricInformation">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationLoadMetricInformation&gt; ApplicationLoadMetricInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ApplicationLoadMetricInformation&gt; ApplicationLoadMetricInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.ApplicationLoadMetricInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationLoadMetricInformation As IList(Of ApplicationLoadMetricInformation)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLoadMetricInformation : System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationLoadMetricInformation&gt;" Usage="System.Fabric.Query.ApplicationLoadInformation.ApplicationLoadMetricInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationLoadMetricInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Ladevorgängen pro Metrik für diese Anwendungsinstanz ab.
            </summary>
        <value>
            Die Liste der Ladevorgängen pro Metrik für diese Anwendungsinstanz. Für jede Metrik, die im definierte <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> Anwendung erstellt oder aktualisiert wurde werden eine Instanz des <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" /> in dieser Liste.
            </value>
        <remarks>
            Für Anwendungen, die keine Anwendungskapazität definiert wird diese Liste leer sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodes">
      <MemberSignature Language="C#" Value="public long MaximumNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaximumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.MaximumNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MaximumNodes : int64" Usage="System.Fabric.Query.ApplicationLoadInformation.MaximumNodes" />
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
            Ruft die maximale Anzahl von Knoten, in denen diese Anwendung instanziiert werden kann.
            </summary>
        <value>
          <para>
            Anzahl der Knoten, die diese Anwendung zulässig ist, umfassen.
            Dieser Wert ist gleich <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> festgelegt wurde, wenn die Anwendung erstellt oder aktualisiert wurde.
            </para>
        </value>
        <remarks>
            Für Anwendungen, die keine Anwendungskapazität definiert wird dieser Wert 0 (null) sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodes">
      <MemberSignature Language="C#" Value="public long MinimumNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MinimumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.MinimumNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MinimumNodes : int64" Usage="System.Fabric.Query.ApplicationLoadInformation.MinimumNodes" />
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
            Ruft die minimale Anzahl von Knoten für diese Anwendung ab.
            </summary>
        <value>
          <para>
            Anzahl der Knoten, auf dem Service Fabric Kapazität im Cluster für diese Anwendungsinstanz reservieren.
            Dieser Wert ist gleich <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" /> festgelegt wurde, wenn die Anwendung erstellt oder aktualisiert wurde.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.ApplicationLoadInformation.Name" />
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
            Ruft den Namen der Anwendung ab oder legt diesen fest.
            </summary>
        <value>
            Der Namen der Anwendung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCount">
      <MemberSignature Language="C#" Value="public long NodeCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.NodeCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeCount As Long" />
      <MemberSignature Language="F#" Value="member this.NodeCount : int64" Usage="System.Fabric.Query.ApplicationLoadInformation.NodeCount" />
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
            Ruft die Anzahl der Knoten, auf denen diese Anwendung instanziiert wird.
            </summary>
        <value>
          <para>
            Die Anzahl der Knoten, auf denen diese Anwendung derzeit instanziiert wird.
            </para>
        </value>
        <remarks>
            Für Anwendungen, die keine Anwendungskapazität definiert wird dieser Wert 0 (null) sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationLoadInformation.ToString " />
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
            Details der Schöndruck <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.
            </para>
        </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</returns>
        <remarks>To be added.</remarks>
        <example>
            "Parameter" ApplicationName "": "Fabric: / LoadBalancingAppType", "MinimumNodes": 0, "MaximumNodes": 0, "nodename": 0, "ApplicationLoadMetricInformation":]
            </example>
      </Docs>
    </Member>
  </Members>
</Type>