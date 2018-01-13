<Type Name="IImageStoreProgressHandler" FullName="System.Fabric.IImageStoreProgressHandler">
  <TypeSignature Language="C#" Value="public interface IImageStoreProgressHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IImageStoreProgressHandler" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IImageStoreProgressHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IImageStoreProgressHandler" />
  <TypeSignature Language="F#" Value="type IImageStoreProgressHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>Definiert das Verhalten, das ein Status Handler implementieren müssen Prozess Statusinformationen von Image Store-Vorgängen</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetUpdateInterval">
      <MemberSignature Language="C#" Value="public TimeSpan GetUpdateInterval ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype System.TimeSpan GetUpdateInterval() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IImageStoreProgressHandler.GetUpdateInterval" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUpdateInterval () As TimeSpan" />
      <MemberSignature Language="F#" Value="abstract member GetUpdateInterval : unit -&gt; TimeSpan" Usage="iImageStoreProgressHandler.GetUpdateInterval " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft das Intervall, an welchen, das Fortschritt Informationen veröffentlicht werden, einige Details, die Abfrage verwenden (z. B. Anwendungspaket hochladen und Herunterladen von Fortschritt) ab. 0 (null) zurückgeben, verwenden Sie die Systemstandard 2 Sekunden.</para>
        </summary>
        <returns>
          <para>Die <see cref="T:System.TimeSpan" /> , die das Updateintervall Status darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateProgress">
      <MemberSignature Language="C#" Value="public void UpdateProgress (long completedItems, long totalItems, System.Fabric.ProgressUnitType itemType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateProgress(int64 completedItems, int64 totalItems, valuetype System.Fabric.ProgressUnitType itemType) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IImageStoreProgressHandler.UpdateProgress(System.Int64,System.Int64,System.Fabric.ProgressUnitType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateProgress (completedItems As Long, totalItems As Long, itemType As ProgressUnitType)" />
      <MemberSignature Language="F#" Value="abstract member UpdateProgress : int64 * int64 * System.Fabric.ProgressUnitType -&gt; unit" Usage="iImageStoreProgressHandler.UpdateProgress (completedItems, totalItems, itemType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="completedItems" Type="System.Int64" />
        <Parameter Name="totalItems" Type="System.Int64" />
        <Parameter Name="itemType" Type="System.Fabric.ProgressUnitType" />
      </Parameters>
      <Docs>
        <param name="completedItems">Die Anzahl der abgeschlossenen Arbeitsaufgaben.</param>
        <param name="totalItems">Die Gesamtanzahl von Arbeitselementen.</param>
        <param name="itemType">Die Maßeinheit für jede Arbeitsaufgabe.</param>
        <summary>
          <para>Meldet den Fortschritt des aktuellen Vorgangs</para>
        </summary>
        <remarks>Die Gesamtanzahl der Elemente ist nicht immer gewährleistet, die zu Beginn des Vorgangs nicht bekannt sein. In einigen Fällen kann diesen Wert erhöhen, wenn mehr Arbeit während der Verarbeitung ermittelt werden kann.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>