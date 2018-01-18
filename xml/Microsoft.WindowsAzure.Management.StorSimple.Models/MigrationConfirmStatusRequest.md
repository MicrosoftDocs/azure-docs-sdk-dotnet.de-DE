<Type Name="MigrationConfirmStatusRequest" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest">
  <TypeSignature Language="C#" Value="public class MigrationConfirmStatusRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationConfirmStatusRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationConfirmStatusRequest" />
  <TypeSignature Language="F#" Value="type MigrationConfirmStatusRequest = class" />
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
            <span data-ttu-id="8d274-101">Diese Klasse stellt migrationsanforderung zu bestätigen.</span><span class="sxs-lookup"><span data-stu-id="8d274-101">This class represents confirm migration request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationConfirmStatusRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8d274-102">Initialisiert eine neue Instanz der MigrationConfirmStatusRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8d274-102">Initializes a new instance of the MigrationConfirmStatusRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationConfirmStatusRequest (System.Collections.Generic.List&lt;string&gt; dataContainerNameList, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.List`1&lt;string&gt; dataContainerNameList, valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest.#ctor(System.Collections.Generic.List{System.String},Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dataContainerNameList As List(Of String), operation As MigrationOperation)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest : System.Collections.Generic.List&lt;string&gt; * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest (dataContainerNameList, operation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataContainerNameList" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="operation" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation" />
      </Parameters>
      <Docs>
        <param name="dataContainerNameList">To be added.</param>
        <param name="operation">To be added.</param>
        <summary>
            <span data-ttu-id="8d274-103">Initialisiert eine neue Instanz der MigrationConfirmStatusRequest-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="8d274-103">Initializes a new instance of the MigrationConfirmStatusRequest class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainerNameList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DataContainerNameList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DataContainerNameList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest.DataContainerNameList" />
      <MemberSignature Language="VB.NET" Value="Public Property DataContainerNameList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DataContainerNameList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest.DataContainerNameList" />
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
            <span data-ttu-id="8d274-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8d274-104">Required.</span></span> <span data-ttu-id="8d274-105">Ruft ab oder legt die Liste der Namen der Volume-Container muss an ein Commit/Rollback</span><span class="sxs-lookup"><span data-stu-id="8d274-105">Gets or sets the list of volume container names which needs to committed/rolled back</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As MigrationOperation" />
      <MemberSignature Language="F#" Value="member this.Operation : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d274-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8d274-106">Required.</span></span> <span data-ttu-id="8d274-107">Ruft ab oder legt den Typ des auszuführenden Vorgangs während der Migration zu bestätigen.</span><span class="sxs-lookup"><span data-stu-id="8d274-107">Gets or sets the type of operation to be performed during confirm migration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>