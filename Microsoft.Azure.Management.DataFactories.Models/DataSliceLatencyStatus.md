<Type Name="DataSliceLatencyStatus" FullName="Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus">
  <TypeSignature Language="C#" Value="public static class DataSliceLatencyStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSliceLatencyStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSliceLatencyStatus" />
  <TypeSignature Language="F#" Value="type DataSliceLatencyStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Status der Daten Slice-Latenzzeit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Late">
      <MemberSignature Language="C#" Value="public const string Late;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Late" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus.Late" />
      <MemberSignature Language="VB.NET" Value="Public Const Late As String " />
      <MemberSignature Language="F#" Value="val mutable Late : string" Usage="Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus.Late" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Datenslice ist späte, wenn der Slice nicht beendeten Status durch die vom Benutzer bestimmt die latenzlänge erreicht hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTime">
      <MemberSignature Language="C#" Value="public const string OnTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string OnTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus.OnTime" />
      <MemberSignature Language="VB.NET" Value="Public Const OnTime As String " />
      <MemberSignature Language="F#" Value="val mutable OnTime : string" Usage="Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus.OnTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Datenslice ist OnTime auf, wenn das Segment einen beendeten Status (Ready/Fehler/FailedValidation / "timedOut") vor der vom Benutzer bestimmt die latenzlänge erreicht hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>