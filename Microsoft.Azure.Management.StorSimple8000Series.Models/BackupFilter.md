<Type Name="BackupFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter">
  <TypeSignature Language="C#" Value="public class BackupFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupFilter" />
  <TypeSignature Language="F#" Value="type BackupFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die OData-Filter für Sicherungen verwendet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BackupFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupFilter (string backupPolicyId = null, string volumeId = null, Nullable&lt;DateTime&gt; createdTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupPolicyId, string volumeId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.#ctor(System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupPolicyId As String = null, Optional volumeId As String = null, Optional createdTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter : string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter (backupPolicyId, volumeId, createdTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupPolicyId" Type="System.String" />
        <Parameter Name="volumeId" Type="System.String" />
        <Parameter Name="createdTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="backupPolicyId">Gibt die BackupPolicyId Sicherungen gefiltert werden sollen. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</param>
        <param name="volumeId">Gibt die VolumeId Sicherungen gefiltert werden sollen. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</param>
        <param name="createdTime">Gibt den Zeitpunkt der Erstellung der Sicherungen gefiltert werden sollen. Nur "größer als oder gleich" und "Kleiner als oder gleich" Operatoren für diese Eigenschaft unterstützt werden.</param>
        <summary>
            Initialisiert eine neue Instanz der BackupFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyId">
      <MemberSignature Language="C#" Value="public string BackupPolicyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupPolicyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.BackupPolicyId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyId As String" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.BackupPolicyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupPolicyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die BackupPolicyId Sicherungen gefiltert werden sollen. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createdTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den Zeitpunkt der Erstellung der Sicherungen gefiltert werden. Nur "größer als oder gleich" und "Kleiner als oder gleich" Operatoren für diese Eigenschaft unterstützt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeId">
      <MemberSignature Language="C#" Value="public string VolumeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VolumeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.VolumeId" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeId As String" />
      <MemberSignature Language="F#" Value="member this.VolumeId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.VolumeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die VolumeId Sicherungen gefiltert werden sollen.
            Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>