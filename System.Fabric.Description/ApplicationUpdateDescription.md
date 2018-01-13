<Type Name="ApplicationUpdateDescription" FullName="System.Fabric.Description.ApplicationUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpdateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpdateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpdateDescription" />
  <TypeSignature Language="F#" Value="type ApplicationUpdateDescription = class" />
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
            Beschreibt ein Update der Anwendungskapazität, die aktualisiert werden<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpdateDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationUpdateDescription : Uri -&gt; System.Fabric.Description.ApplicationUpdateDescription" Usage="new System.Fabric.Description.ApplicationUpdateDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">Der URI des Instanznamens Anwendung.</param>
        <summary>
            Erstellt eine neue Instanz von <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateDescription (Uri applicationName, bool removeApplicationCapacity, long minimumNodes, long maximumNodes, System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, bool removeApplicationCapacity, int64 minimumNodes, int64 maximumNodes, class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpdateDescription.#ctor(System.Uri,System.Boolean,System.Int64,System.Int64,System.Collections.Generic.IList{System.Fabric.Description.ApplicationMetricDescription})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, removeApplicationCapacity As Boolean, minimumNodes As Long, maximumNodes As Long, metrics As IList(Of ApplicationMetricDescription))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationUpdateDescription : Uri * bool * int64 * int64 * System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; -&gt; System.Fabric.Description.ApplicationUpdateDescription" Usage="new System.Fabric.Description.ApplicationUpdateDescription (applicationName, removeApplicationCapacity, minimumNodes, maximumNodes, metrics)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="removeApplicationCapacity" Type="System.Boolean" />
        <Parameter Name="minimumNodes" Type="System.Int64" />
        <Parameter Name="maximumNodes" Type="System.Int64" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" />
      </Parameters>
      <Docs>
        <param name="applicationName">Der URI des Instanznamens Anwendung.</param>
        <param name="removeApplicationCapacity">
            Gibt an, ob die Anwendungskapazität entfernt werden soll (siehe <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />).
            </param>
        <param name="minimumNodes">
            Minimale Anzahl von Knoten (siehe <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />).
            </param>
        <param name="maximumNodes">
            Maximale Anzahl von Knoten (siehe <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />)
            </param>
        <param name="metrics">
            Kapazitätsmetriken für die Anwendung (siehe <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />)
            </param>
        <summary>
            Erstellt eine neue Instanz der <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> mit Anwendungsparameter-Kapazität.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.ApplicationName" />
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
          <para>Ruft ab oder legt den URI-Namen der Anwendungsinstanz.</para>
        </summary>
        <value>
          <para>Der Anwendungsname.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaximumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaximumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaximumNodes : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von Knoten, in denen diese Anwendung instanziiert werden.
            </summary>
        <value>
          <para>
            Anzahl der Knoten, die diese Anwendung zulässig ist, umfassen. Der Standardwert lautet null.
            Ist er 0 (null), kann die Anwendung auf eine beliebige Anzahl von Knoten im Cluster befinden.
            Wenn dieser Parameter nicht angegeben wird, wenn eine Anwendung zu aktualisieren, bleibt die maximale Anzahl von Knoten unverändert.
            </para>
          <para>
            Wenn dieser Parameter kleiner als <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" /> ein <see cref="T:System.ArgumentException" /> ausgelöst, wenn <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /> aufgerufen wird.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; Metrics;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Metrics As IList(Of ApplicationMetricDescription) " />
      <MemberSignature Language="F#" Value="val mutable Metrics : System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" Usage="System.Fabric.Description.ApplicationUpdateDescription.Metrics" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Metriken für die die Anwendungskapazität definiert ist.
            </summary>
        <returns>
            Gibt die metrische Kapazität der Anwendung. Kapazität wird angegeben, für jede Metrik mit <see cref="T:System.Fabric.Description.ApplicationMetricDescription" />.
            Wenn dieser Parameter nicht festgelegt ist, klicken Sie dann bleiben kapazitätsmetriken Anwendung unverändert bei der Anwendung zu aktualisieren.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MinimumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MinimumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumNodes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MinimumNodes : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Mindestanzahl von Knoten fest.
            </summary>
        <value>
          <para>
            Anzahl der Knoten, auf dem Service Fabric Kapazität im Cluster für diese Anwendung platziert werden reservieren.
            Beachten Sie, dass dies nicht bedeutet, dass die Anwendung unbedingt Replikate für alle diese Knoten verfügen.
            </para>
          <para>
            Wenn dieser Parameter auf NULL gesetzt wird, wird keine Kapazität reserviert werden. Wenn dieser Parameter nicht festgelegt ist, wenn die Anwendung zu aktualisieren, bleibt die minimale Anzahl von Knoten unverändert.
            </para>
          <para>
            Wenn dieser Parameter ist größer als <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> und wenn beide Parameter angegeben werden und dann eine <see cref="T:System.ArgumentException" /> ausgelöst, wenn <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /> aufgerufen wird.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveApplicationCapacity">
      <MemberSignature Language="C#" Value="public bool RemoveApplicationCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoveApplicationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveApplicationCapacity As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoveApplicationCapacity : bool with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />
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
            Ruft ab oder legt das Flag RemoveApplicationCapacity fest.
            </summary>
        <value>
            So löschen Sie alle Parameter, die im Zusammenhang mit der Anwendungskapazität für diese Anwendung verwendet.
            Es ist nicht möglich, dieser Parameter zusammen mit anderen Parametern Anwendungskapazität angeben.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>