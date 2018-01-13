<Type Name="VirtualDiskGroup" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup">
  <TypeSignature Language="C#" Value="public class VirtualDiskGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualDiskGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualDiskGroup" />
  <TypeSignature Language="F#" Value="type VirtualDiskGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diese Klasse stellt die virtuelle Datenträgergruppe (Volumegruppe).
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualDiskGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualDiskGroup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualDiskGroup (string name, System.Collections.Generic.List&lt;string&gt; virtualDiskList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.List`1&lt;string&gt; virtualDiskList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.#ctor(System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, virtualDiskList As List(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup : string * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup (name, virtualDiskList)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="virtualDiskList" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="virtualDiskList">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualDiskGroup-Klasse mit erforderlichen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Ruft ab oder legt die Instanz-Id der Volumegruppe
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Ruft ab oder legt den Namen der Volumegruppe
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationInProgress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.OperationInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationInProgress As OperationInProgress" />
      <MemberSignature Language="F#" Value="member this.OperationInProgress : Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.OperationInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Ruft ab oder legt einen Wert, der angibt, ob jeder Vorgang in Bearbeitung ist
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualDiskList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VirtualDiskList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VirtualDiskList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.VirtualDiskList" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualDiskList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VirtualDiskList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup.VirtualDiskList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Ruft ab oder legt die Liste der Volumes, die Volumegruppe zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>