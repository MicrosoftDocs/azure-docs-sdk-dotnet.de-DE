<Type Name="BMSRPQueryObject" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject">
  <TypeSignature Language="C#" Value="public class BMSRPQueryObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BMSRPQueryObject extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject" />
  <TypeSignature Language="VB.NET" Value="Public Class BMSRPQueryObject" />
  <TypeSignature Language="F#" Value="type BMSRPQueryObject = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b162b-101">Filter, die Liste von Sicherungskopien.</span><span class="sxs-lookup"><span data-stu-id="b162b-101">Filters to list backup copies.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BMSRPQueryObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b162b-102">Initialisiert eine neue Instanz der BMSRPQueryObject-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b162b-102">Initializes a new instance of the BMSRPQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BMSRPQueryObject (Nullable&lt;DateTime&gt; startDate = null, Nullable&lt;DateTime&gt; endDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject.#ctor(System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional startDate As Nullable(Of DateTime) = null, Optional endDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject (startDate, endDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="startDate"><span data-ttu-id="b162b-103">Sicherungskopien, die nach diesem Zeitpunkt erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="b162b-103">Backup copies created after this time.</span></span></param>
        <param name="endDate"><span data-ttu-id="b162b-104">Sicherungskopien, die vor diesem Zeitpunkt erstellt.</span><span class="sxs-lookup"><span data-stu-id="b162b-104">Backup copies created before this time.</span></span></param>
        <summary>
            <span data-ttu-id="b162b-105">Initialisiert eine neue Instanz der BMSRPQueryObject-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b162b-105">Initializes a new instance of the BMSRPQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject.EndDate" />
      <MemberSignature Language="VB.NET" Value="Public Property EndDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject.EndDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b162b-106">Ruft ab, oder legt ihn fest Sicherungskopien, die vor diesem Zeitpunkt erstellt.</span><span class="sxs-lookup"><span data-stu-id="b162b-106">Gets or sets backup copies created before this time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject.StartDate" />
      <MemberSignature Language="VB.NET" Value="Public Property StartDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject.StartDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b162b-107">Ruft ab, oder legt ihn fest Sicherungskopien nach diesem Zeitpunkt erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="b162b-107">Gets or sets backup copies created after this time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>