<Type Name="ScheduleRecurrence" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence">
  <TypeSignature Language="C#" Value="public class ScheduleRecurrence" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleRecurrence extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleRecurrence" />
  <TypeSignature Language="F#" Value="type ScheduleRecurrence = class" />
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
            <span data-ttu-id="a6edc-101">Wiederholungszeitplan für Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="a6edc-101">Backup policy recurring schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleRecurrence ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a6edc-102">Initialisiert eine neue Instanz der Klasse ScheduleRecurrence an.</span><span class="sxs-lookup"><span data-stu-id="a6edc-102">Initializes a new instance of the ScheduleRecurrence class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleRecurrence (Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType recurrenceType, int recurrenceValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType recurrenceType, int32 recurrenceValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence.#ctor(Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence : Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType * int -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence (recurrenceType, recurrenceValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recurrenceType" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType" />
        <Parameter Name="recurrenceValue" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="recurrenceType">To be added.</param>
        <param name="recurrenceValue">To be added.</param>
        <summary>
            <span data-ttu-id="a6edc-103">Initialisiert eine neue Instanz der Klasse ScheduleRecurrence mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="a6edc-103">Initializes a new instance of the ScheduleRecurrence class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType RecurrenceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType RecurrenceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence.RecurrenceType" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceType As RecurrenceType" />
      <MemberSignature Language="F#" Value="member this.RecurrenceType : Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence.RecurrenceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6edc-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="a6edc-104">Required.</span></span> <span data-ttu-id="a6edc-105">Der Typ der Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="a6edc-105">The type of the recurrence.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceValue">
      <MemberSignature Language="C#" Value="public int RecurrenceValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RecurrenceValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence.RecurrenceValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceValue As Integer" />
      <MemberSignature Language="F#" Value="member this.RecurrenceValue : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence.RecurrenceValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6edc-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="a6edc-106">Required.</span></span> <span data-ttu-id="a6edc-107">Der Wiederholungswert für.</span><span class="sxs-lookup"><span data-stu-id="a6edc-107">The recurrence value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>