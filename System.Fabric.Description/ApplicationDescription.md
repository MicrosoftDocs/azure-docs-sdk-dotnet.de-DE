<Type Name="ApplicationDescription" FullName="System.Fabric.Description.ApplicationDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationDescription" />
  <TypeSignature Language="F#" Value="type ApplicationDescription = class" />
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
      <para>Beschreibt eine Anwendung mit <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Instanziiert eine Instanz des <see cref="T:System.Fabric.Description.ApplicationDescription" /> Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationDescription (Uri applicationName, string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationDescription.#ctor(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, applicationTypeName As String, applicationTypeVersion As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationDescription : Uri * string * string -&gt; System.Fabric.Description.ApplicationDescription" Usage="new System.Fabric.Description.ApplicationDescription (applicationName, applicationTypeName, applicationTypeVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI des Instanznamens Anwendung.</para>
        </param>
        <param name="applicationTypeName">
          <para>Der Name des Anwendungstyps.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die Version des Anwendungstyps.</para>
        </param>
        <summary>
          <para>Instanziiert eine Instanz des <see cref="T:System.Fabric.Description.ApplicationDescription" /> mit den Instanznamen für die Anwendung, der Name des Anwendungstyps und die Version der Anwendung.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationDescription (Uri applicationName, string applicationTypeName, string applicationTypeVersion, System.Collections.Specialized.NameValueCollection applicationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string applicationTypeName, string applicationTypeVersion, class System.Collections.Specialized.NameValueCollection applicationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationDescription.#ctor(System.Uri,System.String,System.String,System.Collections.Specialized.NameValueCollection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, applicationTypeName As String, applicationTypeVersion As String, applicationParameters As NameValueCollection)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationDescription : Uri * string * string * System.Collections.Specialized.NameValueCollection -&gt; System.Fabric.Description.ApplicationDescription" Usage="new System.Fabric.Description.ApplicationDescription (applicationName, applicationTypeName, applicationTypeVersion, applicationParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="applicationParameters" Type="System.Collections.Specialized.NameValueCollection" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI des Instanznamens Anwendung.</para>
        </param>
        <param name="applicationTypeName">
          <para>Der Name des Anwendungstyps.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die Version des Anwendungstyps.</para>
        </param>
        <param name="applicationParameters">
          <para>Die Auflistung von Name-Wert-Paare für die Parameter, die in der ApplicationManifest.xml angegeben werden.</para>
        </param>
        <summary>
          <para>Instanziiert eine Instanz des <see cref="T:System.Fabric.Description.ApplicationDescription" /> mit den Instanznamen für die Anwendung, der Name des Anwendungstyps, die Version der Anwendung und die Auflistung der Anwendungsparameter.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ApplicationDescription.ApplicationName" />
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
    <Member MemberName="ApplicationParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ApplicationParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.ApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationParameters As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ApplicationParameters : System.Collections.Specialized.NameValueCollection" Usage="System.Fabric.Description.ApplicationDescription.ApplicationParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Auflistung von Name-Wert-Paare für die Parameter, die in der ApplicationManifest.xml angegeben werden.</para>
        </summary>
        <value>
          <para>Die Auflistung von Name-Wert-Paare für die Parameter, die in der ApplicationManifest.xml angegeben werden.</para>
        </value>
        <remarks>
            Die maximale zulässige Länge eines Parameterwerts ist 1024 * 1024 Zeichen (einschließlich das abschließende Nullzeichen).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string with get, set" Usage="System.Fabric.Description.ApplicationDescription.ApplicationTypeName" />
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
          <para>Ruft ab oder legt den Namen des Anwendungstyps Service Fabric.</para>
        </summary>
        <value>
          <para>Der Name des Anwendungstyps.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string with get, set" Usage="System.Fabric.Description.ApplicationDescription.ApplicationTypeVersion" />
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
          <para>Ruft ab oder legt die Version des Anwendungstyps.</para>
        </summary>
        <value>
          <para>Die Anwendungstypversion.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodes">
      <MemberSignature Language="C#" Value="public long MaximumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaximumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MaximumNodes : int64 with get, set" Usage="System.Fabric.Description.ApplicationDescription.MaximumNodes" />
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
            Ruft ab oder legt die maximale Anzahl von Knoten, in denen diese Anwendung instanziiert werden.
            </summary>
        <value>
          <para>
            Anzahl der Knoten, die diese Anwendung zulässig ist, umfassen. Der Standardwert lautet null.
            Ist er 0 (null), kann die Anwendung eine beliebige Anzahl von Knoten im Cluster umfassen.
            </para>
          <para>
            Wenn dieser Parameter kleiner als <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" /> ein <see cref="T:System.ArgumentException" /> ausgelöst, wenn <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription)" /> aufgerufen wird.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; Metrics;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Metrics As IList(Of ApplicationMetricDescription) " />
      <MemberSignature Language="F#" Value="val mutable Metrics : System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" Usage="System.Fabric.Description.ApplicationDescription.Metrics" />
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
            Gibt die metrische Kapazität der Anwendung. Kapazität für jede Metrik angegeben wird, mithilfe von <see cref="T:System.Fabric.Description.ApplicationMetricDescription" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodes">
      <MemberSignature Language="C#" Value="public long MinimumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MinimumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MinimumNodes : int64 with get, set" Usage="System.Fabric.Description.ApplicationDescription.MinimumNodes" />
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
            Ruft ab oder legt die Mindestanzahl von Knoten, auf dem Service Fabric-Kapazität für diese Anwendung reserviert.
            </summary>
        <value>
          <para>
            Anzahl der Knoten, auf dem Service Fabric Kapazität im Cluster für diese Anwendung platziert werden reservieren.
            Beachten Sie, dass dies nicht bedeutet, dass die Anwendung unbedingt Replikate für alle diese Knoten verfügen.
            </para>
          <para>
            Wenn dieser Parameter auf NULL gesetzt wird, wird keine Kapazität reserviert werden.
            </para>
          <para>
            Wenn dieser Parameter ist größer als <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> ein <see cref="T:System.ArgumentException" /> ausgelöst, wenn <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription)" /> aufgerufen wird.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>