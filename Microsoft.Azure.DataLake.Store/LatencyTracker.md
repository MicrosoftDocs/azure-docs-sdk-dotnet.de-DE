<Type Name="LatencyTracker" FullName="Microsoft.Azure.DataLake.Store.LatencyTracker">
  <TypeSignature Language="C#" Value="public class LatencyTracker" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LatencyTracker extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.LatencyTracker" />
  <TypeSignature Language="VB.NET" Value="Public Class LatencyTracker" />
  <TypeSignature Language="F#" Value="type LatencyTracker = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             Einzelner Eintrag, durch Kommas getrennt:
                  1. Clientanforderungs-ID
                  2. Wartezeit in Millisekunden
                  3. Fehlercode (falls es sich um eine Anforderung nicht erfüllt)
                  4. Vorgang
                  5. Anforderung und Antwort body Größe (sofern verfügbar, NULL andernfalls)
                  6. Instanz des ADLStoreClient (pro Instanz auf diesem virtuellen Computer eine eindeutige Nummer)
            
                 Mehrere Einträge können auf eine einzelne Anforderung werden. Einträge werden durch Semikolons getrennt ein Limit Max. Einträge für eine einzelne Anforderung auf drei, beschränken in HTTP-Anforderungsgröße zu erhöhen, voneinander getrennt.
                 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LatencyTracker ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.LatencyTracker.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public static void Disable ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Disable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.LatencyTracker.Disable" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Disable ()" />
      <MemberSignature Language="F#" Value="static member Disable : unit -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.LatencyTracker.Disable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Deaktiviert die Latenz tracker
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>