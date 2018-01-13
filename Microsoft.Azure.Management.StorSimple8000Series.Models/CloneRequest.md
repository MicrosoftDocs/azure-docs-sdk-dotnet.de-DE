<Type Name="CloneRequest" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest">
  <TypeSignature Language="C#" Value="public class CloneRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloneRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class CloneRequest" />
  <TypeSignature Language="F#" Value="type CloneRequest = class" />
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
            Der Auftrag klonanforderung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloneRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CloneRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloneRequest (string targetDeviceId, string targetVolumeName, System.Collections.Generic.IList&lt;string&gt; targetAccessControlRecordIds, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement backupElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetDeviceId, string targetVolumeName, class System.Collections.Generic.IList`1&lt;string&gt; targetAccessControlRecordIds, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement backupElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest : string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest (targetDeviceId, targetVolumeName, targetAccessControlRecordIds, backupElement)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetDeviceId" Type="System.String" />
        <Parameter Name="targetVolumeName" Type="System.String" />
        <Parameter Name="targetAccessControlRecordIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="backupElement" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement" />
      </Parameters>
      <Docs>
        <param name="targetDeviceId">Die Pfad-ID des Geräts, der als das Klonziel fungiert.</param>
        <param name="targetVolumeName">Der Name des neuen Volumes, der erstellt wird und die Sicherung werden in geklont werden.</param>
        <param name="targetAccessControlRecordIds">Die Liste der Path-IDs der zugriffssteuerungsdatensatz, der neu geklonte Volume zugeordnet werden soll.</param>
        <param name="backupElement">Die backup-Element, das geklont wird.</param>
        <summary>
            Initialisiert eine neue Instanz der CloneRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupElement">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement BackupElement { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement BackupElement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.BackupElement" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupElement As BackupElement" />
      <MemberSignature Language="F#" Value="member this.BackupElement : Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.BackupElement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupElement")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der backup-Element, das geklont wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetAccessControlRecordIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TargetAccessControlRecordIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TargetAccessControlRecordIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.TargetAccessControlRecordIds" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetAccessControlRecordIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TargetAccessControlRecordIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.TargetAccessControlRecordIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetAccessControlRecordIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Path-IDs der zugriffssteuerungsdatensatz, der neu geklonte Volume zugeordnet werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDeviceId">
      <MemberSignature Language="C#" Value="public string TargetDeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetDeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.TargetDeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDeviceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetDeviceId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.TargetDeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDeviceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Pfad-ID des Geräts, der als das Klonziel fungiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetVolumeName">
      <MemberSignature Language="C#" Value="public string TargetVolumeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetVolumeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.TargetVolumeName" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetVolumeName As String" />
      <MemberSignature Language="F#" Value="member this.TargetVolumeName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.TargetVolumeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetVolumeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des neuen Volumes, die erstellt wird und die Sicherung werden in geklont werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloneRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>