<Type Name="MultiInstanceSettings" FullName="Microsoft.Azure.Batch.MultiInstanceSettings">
  <TypeSignature Language="C#" Value="public class MultiInstanceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiInstanceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.MultiInstanceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiInstanceSettings" />
  <TypeSignature Language="F#" Value="type MultiInstanceSettings = class&#xA;    interface ITransportObjectProvider&lt;MultiInstanceSettings&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Einstellungen auf, die angeben, wie eine Aufgabe mit mehreren Instanzen ausgeführt werden soll. Mit mehreren Instanzen Tasks werden häufig verwendet, um MPI-Aufgaben zu unterstützen. Weitere Informationen finden Sie unter https://azure.microsoft.com/documentation/articles/batch-mpi/.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings (string coordinationCommandLine, Nullable&lt;int&gt; numberOfInstances = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string coordinationCommandLine, valuetype System.Nullable`1&lt;int32&gt; numberOfInstances) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.MultiInstanceSettings.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinationCommandLine As String, Optional numberOfInstances As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.MultiInstanceSettings : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.MultiInstanceSettings" Usage="new Microsoft.Azure.Batch.MultiInstanceSettings (coordinationCommandLine, numberOfInstances)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinationCommandLine" Type="System.String" />
        <Parameter Name="numberOfInstances" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinationCommandLine">Der Befehl, auf die Knoten für die Koordination zwischen der Unteraufgaben Instanzen ausgeführt werden.</param>
        <param name="numberOfInstances">Die Anzahl der Compute-Knoten, die von der Aufgabe mit mehreren Instanzen erforderlich sind.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.MultiInstanceSettings" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; CommonResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; CommonResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.CommonResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.CommonResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.CommonResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder Festlegen einer Liste von Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile Koordinierung heruntergeladen wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Unterschied zwischen allgemeinen Ressourcendateien und Ressourcendateien Aufgabe ist, dass allgemeine Ressourcendateien für alle Unteraufgaben an, einschließlich der primären heruntergeladen werden, während nur für die primäre Aufgabe Ressourcendateien heruntergeladen werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CoordinationCommandLine">
      <MemberSignature Language="C#" Value="public string CoordinationCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CoordinationCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CoordinationCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CoordinationCommandLine : string with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Befehls zum Ausführen auf Instanzen der Knoten für die Koordination zwischen die Unteraufgaben an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.NumberOfInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.NumberOfInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl von Serverknoten, die von der Aufgabe mit mehreren Instanzen erforderlich sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>